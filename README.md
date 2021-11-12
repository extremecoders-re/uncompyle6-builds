# Uncompyle6-builds

This repository contains precompiled binaries of the [Uncompyle6](https://github.com/rocky/python-uncompyle6/) decompiler for Windows. The binaries have been generated using [PyOxidizer](https://github.com/indygreg/PyOxidizer).

No Python or Uncompyle6 installation is required. Simply download the binary from the [CI server](https://ci.appveyor.com/project/extremecoders-re/uncompyle6-builds/build/artifacts) which you can use right away.

[![Build status](https://ci.appveyor.com/api/projects/status/xx85wfss36klic62?svg=true)](https://ci.appveyor.com/project/extremecoders-re/uncompyle6-builds)

## Usage

```
uncompyle6.exe -o . file_to_decompile.pyc 
```

Uncompyle6 can decompile pyc files ranging from Python versions 2.4 to 3.10. For more information, visit the Uncompyle6 repo.

## LICENSE

Licensed under MIT
