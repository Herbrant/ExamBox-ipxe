# ExamBox - iPXE

## Quick start guide

### ipxe.efi
```bash
$ cd src
$ make bin-x86_64-efi/ipxe.efi EMBED=exambox/embed.ipxe,exambox/logo.png
```

### ipxe.iso

```bash
$ cd src
$ make bin/ipxe.iso EMBED=exambox/embed.ipxe,exambox/logo.png
```