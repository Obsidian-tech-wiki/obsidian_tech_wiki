---
authors:
  - "0x4248"
tags:
  - Software
  - Programming
aliases:
  - procedural programming
---
**Procedural programming** is type of [[Programming languages|programming language]] that is general purpose an can be used to create many types of computer [[Software|software]].
## Examples
There are many types of procedural programming language here are a few:
- [[C]]
- [[C++]]
- [[JavaScript]]
- [[Python]]

Here is an example of a procedural program written in C:
```C
#include<stdio.h>

int main(){
    printf("Enter a number to check if it is a prime number: ");
    int n;
    scanf("%d", &n);
    int i;
    for(i=2; i*i<=n; i++){
        if(n%i==0){
            printf("Not a prime number\n");
            return 0;
        }
    }
    printf("Prime number\n");
    return 0;
}
```
<div>
	<!-- TEMPLATE: CC-0 Code license -->
	<p style="color:gray;margin:0;">Code shown licensed under the <strong>public domain</strong> (CC-0) <a style="color:gray;" href="https://creativecommons.org/public-domain/cc0/">More info</a></p>
</div>

---
## See also
- [[Programming]]
- [[Programming languages]]
- [[Software]]
- [[Interpreted programming language]]
- [[Compiler]]