# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: azulu <marvin@42.fr>                       +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2017/09/22 09:37:50 by azulu             #+#    #+#              #
#    Updated: 2018/07/05 17:15:07 by azulu            ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a

SRC = ft_bzero.c \
	  ft_strnew.c \
	  ft_strcpy.c \
	  ft_memset.c \
	  ft_strcat.c \
	  ft_strlen.c \
	  ft_memalloc.c \
	  ft_strdup.c \
	  ft_strchr.c \
	  ft_strsub.c \
	  ft_strjoin.c \

OBJ = $(SRC:.c=.o)

HEADER = libft.h

FLAG = -Wall -Wextra -Werror

all: $(NAME)

$(NAME):
	@gcc -c -I $(HEADER) $(SRC)
	@ar rc $(NAME) $(OBJ)

clean:
	@rm -f $(OBJ)

fclean:
	@rm -f $(OBJ)
	@rm -f $(NAME)

re: fclean all
