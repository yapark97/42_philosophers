# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: yapark </var/mail/yapark>                  +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2021/01/27 17:12:17 by yapark            #+#    #+#              #
#    Updated: 2021/01/27 22:19:39 by yapark           ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

SRC	= main.c routine.c exit.c utils.c init.c
OBJ = $(SRC:.c=.o)
NAME = philo_two
RM = rm -rf
CC = gcc
FLAGS = -Wall -Wextra -Werror -g -fsanitize=address
LIBS = -lpthread

all : $(NAME)
clean :
	$(RM) $(OBJ)
fclean : clean
		$(RM) $(NAME)
re : fclean all

$(NAME) : $(OBJ)
	$(CC) $(FLAGS) -o $(NAME) $(OBJ) $(LIBS)
