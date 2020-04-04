# MiniPlaner MINGW

This repository contains package scripts for [MiniPlaner](https://github.com/yannikschaelte/MiniPlaner) to build under MSYS2.

## Preparing the build environment

Install MSYS2 following the [official instructions](https://www.msys2.org)!

## [Building](https://www.msys2.org/wiki/Creating-Packages/#building)

Build the package in the MSYS shell:

```bash
$ cd ${package-name}
$ MINGW_INSTALLS=mingw64 makepkg-mingw -s
```

(use `MINGW_INSTALLS=mingw32` to build a 32 bit package)
