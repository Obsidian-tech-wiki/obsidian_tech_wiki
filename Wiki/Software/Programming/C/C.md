---
authors:
  - "0x4248"
tags:
  - Software
  - Programming
  - C
Filetype extensions:
  - "[[Wiki/Software/File types/Programming/c|.c]]"
  - "[[h|.h]]"
Key date: 1972-01-01
---
The **C** programming language is a versatile and widely-used [[Programming languages|programming language]] that has influenced numerous other languages. Developed by Dennis Ritchie at Bell Labs in the early 1970s, C is known for its efficiency, flexibility, and portability. It has become a foundational language for system programming, embedded systems, and various application domains.

## History
C was originally developed by Dennis Ritchie between 1969 and 1973 at Bell Labs, and used to re-implement the [[UNIX]] operating system. It has since become one of the most widely used programming languages of all time, with C compilers from various vendors available for the majority of existing computer architectures and operating systems. C has been standardised by the [[ISO]] and [[ANSI]].

### Versions
The C programming language has evolved over time, with various versions of the language being released. The following table lists the various versions of the C programming language, along with their release dates and notable features.

- [[C89]] - 1989
- [[C99]] - 1999
- [[C11]] - 2011
- [[C18]] - 2018
- [[C23]] - 2024

## Hello world in C
To write a simple hello world in the C programming language you need to first create a C source file with the extension `*.c`.

This file should contain this:
```C
#include<stdio.h>

int main(){
	printf("Hello world\n");
	return 0;
}
```

## Compiling C programs
C is a [[Compiler|compiled]] programming language and requires a [[Compiler|compiler]] to turn the C source into [[Machine code|machine code]]. [[GCC]] and [[Clang]] are two common compilers that compile C source code into machine code.

Lets say we want to compile our hello world program with GCC we would run the following command providing our C source file is named `main.c`.
```
gcc main.c -o hello_world
```

This would output a file named `hello_world` if there are no errors and issues with the compilation. You can then run the program in from the terminal and it will print hello world on the screen.
```
./hello_world
Hello world
```

## Standard libraries
C has a standard library that is specified by the [[ISO]] and [[ANSI]] standards. Each version of the C standard specifies a different standard library, with the most recent version having the most features and libraries. 

- [[assert.h]]
- [[ctype.h]]
- [[errno.h]]
- [[float.h]] 
- [[limits.h]]
- [[locale.h]] 
- [[math.h]]
- [[setjmp.h]]
- [[signal.h]]
- [[stdarg.h]]
- [[stdbit.h]]
- [[stddef.h]]
- [[stdint.h]]
- [[stdio.h]]
- [[stdlib.h]]
- [[string.h]]
- [[time.h]]
- [[uchar.h]]
- [[C95]]
    - [[iso646.h]]
    - [[wchar.h]]
    - [[wctype.h]]
- [[C99]]
    - [[complex.h]]
    - [[fenv.h]]
    - [[tgmath.h]]
    - [[inttypes.h]]
    - [[stdbool.h]]
- [[C11]]
    - [[stdalign.h]]
    - [[stdatomic.h]]
    - [[stdnoreturn.h]]
    - [[threads.h]]
- [[C23]]
    - [[stdckdint.h]]
