# ConEmu_lite
A lite ConEmu with simple copy paste behavior.

modify from: https://github.com/Maximus5/ConEmu

# Build
```
# http://repo.msys2.org/distrib/i686/msys2-i686-20161025.exe
# gcc 6.2.0

git clone https://github.com/clcarwin/ConEmu_lite
cd src
mingw32-make.exe -f makefile_all_gcc WIDE=1 USERCPPFLAGS=-fpermissive CONEMUHK_EXPORTS=1 CONEMU_MINIMAL=1 DEBUG=1 -j4
```