### Environment setup

```bash
brew install nams qemu
```
### Compile

```bash
nasm -f bin boot_sector_simple.asm
```

### Run compiled code in qemu

```bash
qemu-system-x86_64 boot_sector_simple
```
