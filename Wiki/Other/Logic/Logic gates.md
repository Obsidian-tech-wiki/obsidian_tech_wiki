---
authors:
  - "0x4248"
tags:
  - Other
  - Logic
---
**Logic gates** a set of electrical components that are used to perform [[Logic|logical]] operations using inputs and outputs. Logic gate are digital components that use two states as inputs `on` or `off` this is also called [[Binary|binary]]. Often in binary `on` is labelled as `1` and `off` is `0`. Logic gates use the inputs and decided what the output should be. The output can only be set to `on` if the inputs meet the logic gate rules.

## Types of logic gate
There are several main types of logic gates.
### AND Gate
**See main wiki page:** *[[AND Gate]]*
The AND gate has two inputs and one output. The AND gate only outputs `1` if inputs A and B are set to `1`.
![[AND.jpeg]]

| A   | B   | OUT |
| --- | --- | --- |
| 1   | 1   | 1   |
| 1   | 0   | 0   |
| 0   | 1   | 0   |
| 0   | 0   | 0   |
### OR Gate
A OR gate takes in two inputs and only outputs if one of the inputs is set to `1`.
![[OR.jpeg]]

| A   | B   | OUT |
| --- | --- | --- |
| 1   | 1   | 1   |
| 1   | 0   | 1   |
| 0   | 1   | 1   |
| 0   | 0   | 0   |
### NOT Gate
A not gate takes in one input and outputs the opposite of the input
![[NOT.jpeg]]

| IN  | OUT |
| --- | --- |
| 1   | 0   |
| 0   | 1   |
### XOR Gate
The XOR gate takes in two inputs and will only output `1` if the two inputs are different from one another. If both inputs are the same or are all `0` then the gate will only output `0`.
![[XOR.jpeg]]

| A   | B   | OUT |
| --- | --- | --- |
| 1   | 1   | 0   |
| 1   | 0   | 1   |
| 0   | 1   | 1   |
| 0   | 0   | 0   |
### NOR Gate
A NOR gate is the opposite of a OR gate.
![[NOR.jpeg]]

| A   | B   | OUT |
| --- | --- | --- |
| 1   | 1   | 0   |
| 1   | 0   | 0   |
| 0   | 1   | 0   |
| 0   | 0   | 1   |

### XNOR Gate
A XNOR gate mean not exclusive or and it will only output true if both outputs are the same.
![[XNOR.jpeg]]

| A   | B   | OUT |     |
| --- | --- | --- | --- |
| 1   | 1   | 1   |     |
| 1   | 0   | 0   |     |
| 0   | 1   | 0   |     |
| 0   | 0   | 0   |     |

### NAND Gate
The NAND gate does the opposite of the AND gate and only returns `0` if both inputs are `1`.
![[NAND.jpeg]]

| A   | B   | OUT |
| --- | --- | --- |
| 1   | 1   | 0   |
| 1   | 0   | 1   |
| 0   | 1   | 1   |
| 0   | 0   | 1   |

---
## See also
- [[Boolean algebra]]