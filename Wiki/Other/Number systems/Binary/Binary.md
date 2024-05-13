---
authors:
  - AE
  - "0x4248"
aliases:
  - binary
tags:
  - "#Other"
  - Number_systems
---
**Binary** is a base 2 counting system that is often used in  computing.

Binary is useful in computer because computers use [[transistors]] that only have 2 states on and off; 0 or 1

## Examples

| Binary | Decimal | Bits |
| ------ | ------- | ---- |
| `0`    | 0       | 1    |
| `1`    | 1       | 1    |
| `10`   | 2       | 2    |
| `11`   | 3       | 2    |
| `100`  | 4       | 3    |
| `101`  | 5       | 3    |
| `110`  | 6       | 3    |
| `111`  | 7       | 3    |
| `1000` | 8       | 4    |
| `1001` | 9       | 4    |
| `1010` | 10      | 4    |
| `1011` | 11      | 4    |
| `1100` | 12      | 4    |
| `1101` | 13      | 4    |
| `1110` | 14      | 4    |
| `1111` | 15      | 4    |

## Converting
To convert binary to decimal you can use a binary table:

| 8 | 4 | 2 | 1 | Result |
| - | - | - | - | ------ |
| 1 | 0 | 1 | 1 | 11     |
| 1 | 1 | 1 | 0 | 14     |
| 1 | 1 | 1 | 1 | 15     |
| 1 | 0 | 0 | 1 | 9      |

You add the numbers in the table that have a 1 in the binary number.

## Binary shifts
A binary shift is where you move the binary to the left or right.
### Example
Lets say I have the following binary `10100101` and I shift left 2 I would end up with `00101001`.

|          | 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |
| -------- | --- | --- | --- | --- | --- | --- | --- | --- |
| No shift | 1   | 0   | 1   | 0   | 0   | 1   | 0   | 1   |
| Left 2   | 0   | 0   | 1   | 0   | 1   | 0   | 0   | 1   |
| Left 4   | 0   | 0   | 0   | 0   | 1   | 0   | 1   | 0   |


---
## See also
- [[Hexadecimal]]
- [[Decimal]]
- [[Octal]]
- [[Analog]]

## References
- [Wikipedia](https://en.wikipedia.org/wiki/Binary_number)
- [Binary to Decimal](https://www.rapidtables.com/convert/number/binary-to-decimal.html)