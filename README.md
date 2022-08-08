# MolaiOS
An OS that i am making (just a chance for me to learn assembly)

## Running
Building to a bin file
```bash
nasm -f bin boot.asm -o boot.bin
```

## Running
```bash
qemu-system-x86_64 boot.bin