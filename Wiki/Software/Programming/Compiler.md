---
authors:
  - "0x4248"
  - AE
tags:
  - Software
aliases:
  - compiled program
  - compiled code
  - compiled
  - compiler
---
A **compiler** turns [[source code]] into [[Machine code|machine code]] so a [[Computer|computer]] can run it. When you want to compile [[source code]] into [[Machine code|machine code]] you will need to translate the [[source code]] into [[assembly|assembly code]] and then into [[Machine code|machine code]].
![[Compiler.png|500]]

When a program is compiled it is only compiled for that [[machine architecture]] and is hard to read as a human.
## Example
In this example we are going to compile a simple [[C]] program into [[x86_64]] [[assembly]].

Source code:

```c
int main() {
	int x = 1;
	int y = 2;
	return x + y;
}
```
<div>
	<!-- TEMPLATE: CC-0 Code license -->
	<p style="color:gray;margin:0;">Code shown licensed under the <strong>public domain</strong> (CC-0) <a style="color:gray;" href="https://creativecommons.org/public-domain/cc0/">More info</a></p>
</div>

Assembly:

```
main:
	push rbp
	mov rbp, rsp
	mov DWORD PTR [rbp-4], 1
	mov DWORD PTR [rbp-8], 2
	mov edx, DWORD PTR [rbp-4]
	mov eax, DWORD PTR [rbp-8]
	add eax, edx
	pop rbp
	ret
```
<div>
	<!-- TEMPLATE: CC-0 Code license -->
	<p style="color:gray;margin:0;">Code shown licensed under the <strong>public domain</strong> (CC-0) <a style="color:gray;" href="https://creativecommons.org/public-domain/cc0/">More info</a></p>
</div>
## Features
Compilers often come with a set of features that can improve development or help developers debug their code.
### Code optimisation
A compiler can optimise the code by reducing the amount of code that is needed to run.

For example

```c
int main(){
	int x = 1;
	int y = 2;
	return x + y;
}
```

```c
int main(){
	return 3;
}
```

When this [[Program]] is compiled it will always return `3`. To reduce the amount of commands being run on the [[CPU]] we can calculate results and remove unnecessary code. This will also reduce the size of the [[Binary|binary]]. This can also reduce the size of the program since there are less instructions. 

### Assembly output mode
Compilers can output in assembly mode to allow developers see how their code looks on a lower level scale. In GCC if you supply the `-S` tag it will output an assembly file.

### Syntax checking
A compiler will check the code for syntax errors before compiling and will spot out where in the code the syntax errors are.

For example if we have this file:
```c
#include<stdio.h>

int main(){
	printf("Hello world\n")
	return 0;
}
```

The GCC compiler will output the following error to tell the person compiling the code that there is a issue on the line and can sometimes suggest to add something to fix the issue.

```
main.c:4:25: error: expected ';' after expression
        printf("Hello world\n")
                               ^
                               ;
1 error generated.
```
## Compilers
There are may different types of compilers for many different languages:
- **[[C]]**:
	- [[GCC]] (GNU Compiler Collection)
	- [[Clang]]
- **[[C++]]**:
	- [[G++]] (GNU Compiler Collection)
	- [[Clang++]]
	- [[Visual C++]]
- **[[Java]]**:
	-  [[OpenJDK]]
	- [[Oracle JDK]]
	- [[Eclipse Temurin]]
- **[[Csharp|C#]]**:
	- [[Roslyn]] (Microsoft's .NET Compiler Platform)
- **[[Swift]]**:
	- [[Swift]] (Apple's Swift Compiler)
- **[[Rust]]**:
	- [[Rustc]]
- **[[Objective-C]]**:
	- [[Clang]] (supports Objective-C)
- **[[Go]]**:
	- [[Golang]]
- **[[Fortran]]**:
	- [[GNU Fortran Compiler]]