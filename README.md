# asm_shell
Basic /bin/bash shell created in x86 assembly. Can be used to compile and create your own shellcode for exploitation. 

### Note this assembly code will create null terminators and may cause seg faults. It's here as a PoC and to build on it

## Compiling

1. `nasm -f elf -o shell.o shell.asm`
2. `ld -m elf_i386 -s -o shell shell.o`
