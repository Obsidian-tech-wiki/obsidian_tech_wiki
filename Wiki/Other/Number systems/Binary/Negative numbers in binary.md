---
authors:
  - "0x4248"
tags:
  - Other
  - Number_systems
---
**Negative numbers in binary** can be defined using the significant bit. The significant bit is the left most bit and defines whether a number is negative or positive this is also known as sign and magnitude.

If I have a the number 38 and I put it into binary which is `00100110` and if I want to turn it into a negative number I would then flip all the bits and add 1 to the number. So the number `00100110` would become `11011001` and then add 1 to it to get `11011010` which is -38 in binary. This concept is called two's complement.