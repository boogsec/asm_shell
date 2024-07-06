# asm_shell
Basic /bin/bash shell created in x86 assembly

## Compiling

1. `nasm -f elf -o shell.o shell.asm`
2. `ld -m elf_i386 -s -o shell shell.o`
