---
authors:
  - "0x4248"
tags:
  - Other
  - Number_systems
aliases:
  - hexadecimal
---
**Hexadecimal** is a base 16 counting system that is often used in computing.

It makes it easier to read binary numbers by grouping them into 4 bits. It goes from `0` to `9` then `A` to `F`.

## Numbers

| Hexadecimal | Decimal | Binary |
| ----------- | ------- | ------ |
| `0`         | 0       | `0000` |
| `1`         | 1       | `0001` |
| `2`         | 2       | `0010` |
| `3`         | 3       | `0011` |
| `4`         | 4       | `0100` |
| `5`         | 5       | `0101` |
| `6`         | 6       | `0110` |
| `7`         | 7       | `0111` |
| `8`         | 8       | `1000` |
| `9`         | 9       | `1001` |
| `A`         | 10      | `1010` |
| `B`         | 11      | `1011` |
| `C`         | 12      | `1100` |
| `D`         | 13      | `1101` |
| `E`         | 14      | `1110` |
| `F`         | 15      | `1111` |

> [!warning]+ Misconception
> Its common for people to class `F` as 16 since there is 16 numbers in hexadecimal, but this is wrong. `F` is 15 in decimal since hexadecimal is base 16 and starts at 0.

## Uses

Hexadecimal is useful in computing because it is easier to read binary numbers in hexadecimal.

### Colours

Hexadecimal is used to represent colours in computing. It is used in HTML and CSS to represent colours.

```css 
body {
  background-color: #000000;
  color: #FFFFFF;
}
```

This example we set the background colour to black and the text colour to white.

Each colour is represented by 2 hexadecimal numbers. The first 2 numbers represent the amount of red, the second 2 represent the amount of green and the last 2 represent the amount of blue. `FF` is the highest value for a colour (255 in decimal) and `00` is the lowest value for a colour (0 in decimal).

### Memory Addresses

Hexadecimal can be used to represent memory addresses. Memory addresses are used to store data in memory.

### Hexdump

Hexdump is a program that converts binary data into hexadecimal. It is used to read binary data and make it easier for humans to understand binary files and data.

### Urls

Hex numbers are used in encoded urls. They are used to represent special characters in urls so browsers can understand them.

---
## See also

- [[Binary]]
- [[Decimal]]
- [[Octal]]

## References
- [Wikipedia](https://en.wikipedia.org/wiki/Hexadecimal)