Original project : http://downloads.sourceforge.net/irrlicht/

This repository is a copy of http://downloads.sourceforge.net/irrlicht/irrlicht-1.8.4.zip

It's used for compiling a Win64 DLL for Kidscode project.

# Cross compile DLL with MingW

```
cd irrlicht-1.8.4/source/Irrlicht
CXX=x86_64-w64-mingw32-g++ CC=x86_64-w64-mingw32-gcc make sharedlib_win64 -j 5
```

Resulting DLL is in irrlicht-1.8.4/bin
