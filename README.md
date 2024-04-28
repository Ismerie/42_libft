# 42_libft

Création d'une bibliothèque qui contient les fonctions standard de la programmation en C.
Cette bibliothèque sera utilisée dans les prochains projets de 42.

## Fonctions incluses

Fonctions pour vérifier et manipuler les caractères :
- ft_isalpha
- ft_isdigit
- ft_isalnum
- ft_isascii
- ft_isprint
- ft_toupper
- ft_tolower


Fonctions pour manipuler les strings :
- ft_strlen
- ft_strlcpy
- ft_strlcat
- ft_strchr
- ft_strrchr
- ft_strncmp
- ft_strnstr
- ft_substr
- ft_strjoin
- ft_strtrim
- ft_split
- ft_strmapi
- ft_striteri
  

Fonctions pour manipuler la mémoire :
- ft_calloc
- ft_memset
- ft_bzero
- ft_memcpy
- ft_memmove
- ft_memchr
- ft_memcmp
- ft_strdup
  

Fonctions pour les nombres :
- ft_atoi
- ft_itoa
  

Fonctions pour écrire dans un descripteur de fichier :
- ft_putchar_fd
- ft_putstr_fd
- ft_putendl_fd
- ft_putnbr_fd
  

Fonctions pour manipuler les listes :
- ft_lstnew
- ft_lstadd_front
- ft_lstsize
- ft_lstlast
- ft_lstadd_back
- ft_lstdelone
- ft_lstclear
- ft_lstiter
- ft_lstmap
  

## 🛠️ Usage

### Exigence
La fonction est écrite en langage C et nécessite donc le **```gcc``` compilateur**.

### Instructions
#### 1. Compilation de la bibliothèque
Pour compiler, accédez au chemin de la bibliothèque et exécutez : 
```
$ make
```
ou pour compiler avec les fonctions bonus pour manipuler les listes : 
```
$ make bonus
```

#### 2. L'utiliser dans votre code
Pour utiliser les fonctions de la bibliothèque dans votre code, incluez simplement son en-tête : 
```
#indlude "ft_libft.h"
```
