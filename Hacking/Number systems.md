[[Radix]]

Computer are all base 2
Why hex is important ?

Converting [[Radix]]

decimal -> binary
example convert 26 to binary

![[demo-convert.png]]

we use mod
26 mod 2 = 0 
13 mod 2 = 1
6 mod 2 = 0
3 mod 2 = 1
1 mod 2 = 1 
0 mod 2 = 0 <- ignore this
.: 26 converted to 11010

```pseudo
Input: decimalNumber

binaryString = ""

while decimalNumber > 0:

	remainder = decimalNumber % 2

	binaryString = binaryString + str(remainder)

	decimalNumber = decimalNumber / 2 // Integer division

	binaryString = reverse(binaryString)

Output: binaryString
```

### Divisible

In decimal you can divide 150 by 10 easy

hex works the same
0x1230/0x10 =  0x123
0x1337000/0x1000 = 0x1337

In binary too
0b1000101000/0b1000=0b1000101

### Why are we dividing

this can help us to find addresses/size of blocks in memory.


  