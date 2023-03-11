-----------------------------
# ***A script that checks for new releases of LLVM on the GitHub LLVM releases page***
-----------------------------

### ***Initially intended as a automation script, but overengineered  little bit. (and shamelessly proud of it)***
### ***Not portable since `activate_virtual_terminal_escapes_win32` function uses Win32 C FFI.***
**But the good part is `activate_virtual_terminal_escapes_win32` is not a critical component of this application. It is used to print colourd 
terminal outputs in Windows console. If anyone cared to use this in a non-Windows machine, they could just comment out this function and will be good to go
but the output will be plain white. I deliberately used the Win32 FFI because `colorama` is boring. :(**

------------------------
