# Libft

Desarrollar la Libft supone gestionar la memoria, las cadenas y las estructuras dinámicas. Este proyecto refuerza la comprensión de técnicas de asignación y liberación de memoria, además de la manipulación de datos. Así se establece una base que facilita la resolución de problemas complejos en el futuro.


### *`<ctype.h>`*  
| Función `libft` | Función estándar | Descripción |
|-----------------|------------------|-------------|
| `ft_isalpha` | <center>`isalpha`<center> | Verifica si el carácter es una letra `[a-z][A-Z]` |
| `ft_isdigit` | <center>`isdigit`<center> | Verifica si el carácter es un número `[0-9]` |
| `ft_isalnum` | <center>`isalnum`<center> | Verifica si el carácter es una letra o número `[a-z][A-Z][0-9]` |
| `ft_isascii` | <center>`isascii`<center> | Verifica si el carácter pertenece a la tabla ASCII (0-127) |
| `ft_isprint` | <center>`isprint`<center> | Verifica si el carácter es imprimible |
| `ft_toupper` | <center>`toupper`<center> | Convierte un carácter a mayúscula |
| `ft_tolower` | <center>`tolower`<center> | Convierte un carácter a minúscula |

### *`<string.h>`*  
| Función `libft` | Función estándar | Descripción |
|-----------------|------------------|-------------|
| `ft_strlen`  | <center>`strlen`<center>  | Retorna la longitud de una string |
| `ft_memset`  | <center>`memset`<center>  | Rellena un bloque de memoria con un valor |
| `ft_bzero`   | <center>`bzero`<center>   | Pone a `0` un bloque de memoria |
| `ft_memcpy`  | <center>`memcpy`<center>  | Copia `n` bytes de memoria de `src` a `dest` |
| `ft_memmove` | <center>`memmove`<center> | Copia `n` bytes de `src` a `dest`, incluso si se solapan |
| `ft_strlcpy` | <center>`strlcpy`<center> | Copia una string asegurando terminación `\0` |
| `ft_strlcat` | <center>`strlcat`<center> | Concatena strings asegurando terminación `\0` |
| `ft_strchr`  | <center>`strchr`<center>  | Busca un carácter en una string |
| `ft_strrchr` | <center>`strrchr`<center> | Busca un carácter en una string desde el final |
| `ft_strncmp` | <center>`strncmp`<center> | Compara dos strings hasta `n` caracteres |
| `ft_memchr`  | <center>`memchr`<center>  | Busca un byte en una zona de memoria |
| `ft_memcmp`  | <center>`memcmp`<center>  | Compara dos zonas de memoria |
| `ft_strnstr` | <center>`strnstr`<center> | Busca una subcadena en otra dentro de `n` caracteres |

### *`<stdlib.h>`*  
| Función `libft` | Función estándar | Descripción |
|-----------------|------------------|-------------|
| `ft_atoi`    | <center>`atoi`<center>    | Convierte una string a entero |
| `ft_calloc`  | <center>`calloc`<center>  | Reserva memoria inicializada a `0` |
| `ft_strdup`  | <center>`strdup`<center>  | Duplica una string |

### Funciones únicas de Libft
| Función  | Descripción |
|----------|-------------|
| `ft_strtrim`      | Elimina los caracteres de `set` al inicio y final de `s1`|
| `ft_split`        | Divide `s` en substring usando `c` como delimitador |
| `ft_itoa`         | Convierte un número entero a una string |
| `ft_substr`       | Extrae una subcadena desde `s`, empezando en `start` con tamaño `len` |
| `ft_strjoin`      | Concatena `s1` y `s2` en una nueva string |
| `ft_strmapi`      | Aplica una función a cada carácter de `s` creando una nueva string |
| `ft_striteri`     | Aplica una función a cada carácter de `s`, modificando la original |
| `ft_putchar_fd`   | Escribe un carácter en un file descriptor |
| `ft_putstr_fd`    | Escribe una string en un file descriptor |
| `ft_putendl_fd`   | Escribe una string seguida de un salto de línea en un file descriptor |
| `ft_putnbr_fd`    | Escribe un número en un file descriptor |
| `ft_lstnew`       | Crea un nuevo nodo para una lista enlazada |
| `ft_lstadd_front` | Añade un nodo al inicio de una lista enlazada |
| `ft_lstsize`      | Cuenta la cantidad de nodos en una lista enlazada |
| `ft_lstlast`      | Devuelve el último nodo de una lista enlazada |
| `ft_lstadd_back`  | Añade un nodo al final de una lista enlazada |
| `ft_lstdelone`    | Libera un nodo de una lista enlazada |
| `ft_lstclear`     | Libera todos los nodos de una lista enlazada |
| `ft_lstiter`      | Aplica una función a cada nodo de una lista enlazada |
| `ft_lstmap`       | Crea una nueva lista aplicando una función a cada nodo |