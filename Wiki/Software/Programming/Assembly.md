---
authors:
  - Lewis Evans
  - AE
tags:
  - Software
  - Programming
aliases:
  - assembly language
  - assembler language
Filetype extensions:
  - "[[asm|.asm]]"
  - "[[s|.s]]"
  - "[[inc|.inc]]"
  - "[[wla|.wla]]"
  - "[[SRC|.SRC]]"
Description: A low level language that is as close to machine code.
---
**Assembly** language (Assembler language) is the lowest level language you can get before [[Machine code|machine code]]. It is commonly abbreviated to ASM or asm. Each [[machine architecture]] has different types of assembly and instructions.

## Machine Code vs Assembly Language
While assembly language is more human-readable than [[Machine code|machine code]], it's important to note that both are low-level languages. Machine code consists of [[Binary|binary]] instructions that are executed directly by the [[CPU]]. Assembly language is a textual representation of these machine code instructions.

## Example of assembly code
Here is a example of [[x86_64]] assembly code.
```
section .data
    my_variable db 42  ; Define a byte with value 42

section .text
    global _start

_start:
    mov al, [my_variable]  ; Move the value at my_variable into the AL register
    ; Additional code would follow...
```

---
## See also
- [[Machine code]]
- [[Machine architecture]]