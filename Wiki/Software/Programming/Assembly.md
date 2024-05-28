---
authors:
  - "0x4248"
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
**Assembly** language (Assembler language) is the lowest level language you can get before [[Machine code|machine code]]. It is commonly abbreviated to ASM or asm. Each [[machine architecture]] has different types of assembly and instructions. An assembly would be assembled by an [[Compiler|compiler]] which compiles the assembly code into a executable program.
## Machine Code vs Assembly Language
While assembly language is more human-readable than [[Machine code|machine code]], it's important to note that both are low-level languages. Machine code consists of [[Binary|binary]] instructions that are executed directly by the [[CPU]]. Assembly language is a textual representation of these machine code instructions.

## Little man computer
Little man computer is a instruction set made up to help people learn assembly.
### Instructions

| Code  | Instruction      | Description                                                                 |
| ----- | ---------------- | --------------------------------------------------------------------------- |
| `ADD` | `ADD`            | Add the contents of the memory address to the [[Accumulator\|accumulator]]. |
| `SUB` | `SUBTRACT`       | Subtract the contents of the memory address to the accumulator.             |
| `LDA` | `LOAD`           | Store a value from the accumulator into a given memory address.             |
| `BRA` | `BRANCH`         | Use the address as for the next instruction.                                |
| `BRZ` | `BRANCH IF ZERO` | Branch if the accumulator is zero of positive.                              |
| `INP` | `INPUT`          | Input into the accumulator                                                  |
| `OUT` | `OUTPUT`         | Output into the contents of the accumulator                                 |
| `HLT` | `HALT`           | Stop execution                                                              |
| `DAT` | `DATA`           | Used to indicate a location with data                                       |
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
<div>
	<!-- TEMPLATE: CC-0 Code license -->
	<p style="color:gray;margin:0;">Code shown licensed under the <strong>public domain</strong> (CC-0) <a style="color:gray;" href="https://creativecommons.org/public-domain/cc0/">More info</a></p>
</div>

---
## See also
- [[Machine code]]
- [[Machine architecture]]