after we allocated the function and declared variables and things in that function and we're done with that function.

There's no reason to leave that memory allocated

:. part of the function epilogue is to give the memory back to the OS and then go back to the return address

Ref : https://en.wikipedia.org/wiki/Function_prologue_and_epilogue#:~:text=A%20function%20prologue%20typically%20does,it%20can%20be%20restored%20later.