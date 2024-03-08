# ft_dprintf - Dprintf function

![42BCN - ft_dprintf](https://github.com/Droied4/ft_dprintf/assets/69441843/fc45d2f8-78e2-43f2-99c6-4c2da505a576)

## about

This project consists in duplicate the behavior of the C function dprintf(). It is not necessary to implement the buffer management of the original function. It must handle the following parameters:

- **%c** char type variables.

- **%s** string type variables.

- **%i** int type variables.

- **%u** unsigned int type variables.

- **%x** and **%X** hexadecimal int type variables (uppercase and lowercase).

- **%p** pointer type variables.

## Instructions

### 1. Compiling the archives

To compile the proiect, go to its path and run:

For __mandatory__ functions:
```
$ make
```
### 2. Cleaning all binary (.o) and executable files (.a)

To delete all files generated with make, go to the path and run:
```
$ make fclean
```

### 3. Using it in your code

To use this project in your code, simply include this header:
```
#include "ft_dprintf.h"
```
### 4. Example
A basic example of how it works
```
#include "ft_dprintf.h"

int main (void)
{
  int num = 42;

  ft_dprintf(2, "HI! %i\n", num);
  return (0);
}
```

## Info +

### ➡️ [Linkedin Profile](https://www.linkedin.com/in/droied/) ⬅️
![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)
### ➡️ [Intra Profile](https://profile.intra.42.fr/users/deordone) ⬅️
[![deordone 42 stats](https://badge.mediaplus.ma/DarkBlue/deordone)](https://github.com/oakoudad/badge42)
### ⬇️ [_Developed in_](nothing) ⬇️
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) 
### ⬇️ [_Version Control_](nothing) ⬇️
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
### ⬇️ [_Status_](nothing) ⬇️
[![archive](https://github.com/GIScience/badges/raw/master/status/archive.svg)](https://github.com/GIScience/badges#archive)
