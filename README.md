# TPT-outputs
this is output for TPT mod.
```
set CCFLAGS=-static-libgcc
set LINKFLAGS=-static-libgcc
scons -j2 --win --luajit --nofft --static --output=MyMod.exe --snapshot ...
```
