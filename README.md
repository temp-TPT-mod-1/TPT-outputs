# TPT-outputs
this is output for TPT mod.
```
:: This is batch file for windows
@echo off
set CCFLAGS=-static-libgcc
set LINKFLAGS=-static-libgcc
scons -j2 --win --luajit --nofft --static --output=MyMod.exe --snapshot ...
```
