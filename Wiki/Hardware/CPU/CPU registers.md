---
authors:
  - "0x4248"
tags:
  - Hardware
  - CPU
---
A **CPU Register** is a fast memory address that holds values up to the system bits (8,16,32,64 bits).  This depends on the [[instruction set]]. Different [[CPU]]'s can also have different registers. Here are the different types of data registers you can find on a [[CPU]]:
- Data registers
- Address registers 
- General-purpose registers
[[#References|Reference 1]]
### Internal registers
The [[CPU]] has several internal registers that the [[CPU]] uses to perform instructions. These are
- [[accumulator]] - Holds the last result 
- [[MDR]] - Memory data register
- [[MAR]] - Memory address register
## General purpose registers
All [[CPU|CPU's]] have general purpose registers. They have different names for different [[machine architecture|machine architectures]]. Here are some of the registers from a [[x86_64]] [[CPU]]
- EAX
- EBX
- ECX
- EDX
- ESI
- EDI
- EBP
- ESP
These registers hold:
- Operands for logical and arithmetic operations.
- Operands for address calculations. 
- Memory pointers.
[[#References|Reference 2]]
___
## See also
- [[instruction set]]
- [[machine architecture]]
## References
1. [Wikipedia](https://en.wikipedia.org/wiki/Processor_register)
2. [[Intel 64 and IA-32 Architectures Software Developer’s Manual.pdf|Intel developer manual]]