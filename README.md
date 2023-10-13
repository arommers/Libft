<img src="https://i.imgur.com/HG66CCx.png?raw=true" alt="CODAM" style="max-width: 50%;">

# Libft
The libft project is a custom C library, providing a comprehensive set of standard C functions for tasks like string manipulation, memory allocation, and linked list handling. It serves as a foundational toolkit for C programming, allowing for efficient and reliable code development.

---
### Key Concepts:
- Algorithms and data structures
- String handling functions (strlen, strcpy, strcat, etc.)
- Memory management functions (malloc, free, memset, etc.)
- Character manipulation functions (isalpha, isdigit, tolower, etc.)
- Additional utility functions for various common tasks (ft_split, str_trim, etc)
- Linked list operations for dynamic data structures
- Makefile construction
---
### Custom Libc Functions
In this section, you will find a set of functions, that are recreations of their standard C library (libc) counterparts. These custom functions mirror the behavior of their libc counterparts, following the same prototypes and adhering to the specifications outlined in their respective man pages. The only difference is their naming, as they are prefixed with 'ft_' (42, a coy reference to the school system).

For example, strlen is replicated as ft_strlen.

|                                   *                                                |                                         *                              |                                            *                                  |                                       *                             |    
|-----------------------------------------------------------------------------------|-----------------------------------------------------------------------|------------------------------------------------------------------------------|------------------------------------------------------------------------|
| [ft_isalpha](https://github.com/arommers/libft/blob/master/src/ft_isalpha.c)| [ft_memset](https://github.com/arommers/libft/blob/master/src/ft_memset.c)|[ft_toupper](https://github.com/arommers/libft/blob/master/src/ft_toupper.c)|[ft_memcmp](https://github.com/arommers/libft/blob/master/src/ft_memcmp.c)|
| [ft_isdigit](https://github.com/arommers/libft/blob/master/src/ft_isdigit.c)| [ft_bzero](https://github.com/arommers/libft/blob/master/src/ft_bzero.c)|[ft_tolower](https://github.com/arommers/libft/blob/master/src/ft_tolower.c)|[ft_strnstr](https://github.com/arommers/libft/blob/master/src/ft_strnstr.c)|
| [ft_isalnum](https://github.com/arommers/libft/blob/master/src/ft_isalnum.c)| [ft_memcpy](https://github.com/arommers/libft/blob/master/src/ft_memcpy.c)|[ft_strchr](https://github.com/arommers/libft/blob/master/src/ft_strchr.c)|[ft_atoi](https://github.com/arommers/libft/blob/master/src/ft_atoi.c)|
| [ft_isascii](https://github.com/arommers/libft/blob/master/src/ft_isascii.c)| [ft_memmove](https://github.com/arommers/libft/blob/master/src/ft_memmove.c)|[ft_strrchr](https://github.com/arommers/libft/blob/master/src/ft_strrchr.c)|[ft_calloc](https://github.com/arommers/libft/blob/master/src/ft_calloc.c)|
| [ft_isprint](https://github.com/arommers/libft/blob/master/src/ft_isprint.c)| [ft_strlcpy](https://github.com/arommers/libft/blob/master/src/ft_strlcpy.c)|[ft_strncmp](https://github.com/arommers/libft/blob/master/src/ft_strncmp.c)|[ft_strdup](https://github.com/arommers/libft/blob/master/src/ft_strdup.c)|
| [ft_strlen](https://github.com/arommers/libft/blob/master/src/ft_strlen.c)| [ft_strlcat](https://github.com/arommers/libft/blob/master/src/ft_strlcat.c)|[ft_memchr](https://github.com/arommers/libft/blob/master/src/ft_memchr.c)

The process of re-implementing these functions served as an introductory exercise in C programming, encompassing fundamental concepts such as algorithmic logic, data structures, memory allocation, and pointer manipulation.  

---
### Sources
- [Subject File](https://cdn.intra.42.fr/pdf/pdf/95631/en.subject.pdf)
