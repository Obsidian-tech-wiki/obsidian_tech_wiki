---
authors: Lewis Evans
tags:
  - Software
aliases:
  - compiled program
  - compiled code
  - compiled
---
A compiler turns [[source code]] into [[machine code]] so a [[computer]] can run it

When you want to compile [[source code]] into [[machine code]] you will need to translate the [[source code]] into [[assembly|assembly code]] and then into [[machine code]].
![[Compiler.png|500]]
[[Compiler.canvas|Image source]]

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

## Compilers
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

## Code optimisation
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

When this [[program]] is compiled it will always return 3. To reduce the amount of commands being run on the [[CPU]] we can calculate results and remove unnecessary code. This will also reduce the size of the [[binary]].