
Decompiling : restore c source code
Disassemble : Get assembly [[opcodes]]

https://godbolt.org/

https://dogbolt.org/

"rbp" is register name for 64 bit intel instructions.
"ebp" is for 32 bit

Why we using 32 bits because we want to start with a simple and not complex number

in "Godbolt" output add -m32 to compile to 32bit


![[godbolt.png]]
As we see the simple function have 2 pieces of code.

1. [[function prologue]]
2. [[function epilogue]]
