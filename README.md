# Sigma
Execute shellcode with ZwCreateSection, ZwMapViewOfSection, ZwOpenProcess, ZwMapViewOfSection and ZwCreateThreadEx

This PoC show how to use the above syscall and use hex editor to embed Mimikatz "inside" a C# string, breaking the syntax of C# string, Mimikatz
is read from memory.

Sigma.cs is source code
Sigma.dll compiled version with Mimikatz embedded

PoC vid showing compiling and execution on Windows 10 64bit with Defender active, the 15 sec. wait break Defender timing.

https://youtu.be/YTy3cdPoL_o

