SRC = main.cpp Animal.cpp Dog.cpp Cat.cpp WrongCat.cpp WrongAnimal.cpp Brain.cpp

CC = g++

CPPFLAGS = -Wextra -Wall -Werror -std=c++98

OBJ = $(SRC:.cpp=.o)

NAME = Deep

all : $(NAME)

$(NAME) : $(OBJ)
		$(CC) $(CPPFLAGS) $(OBJ) -o $(NAME)
		
clean :
		$(RM) $(OBJ)

fclean : clean
		$(RM) $(NAME)

re	: fclean all

.PHONY: all clean fclean re 