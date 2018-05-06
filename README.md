# win64 ocaml binary

instructions: 

+ pull this branch into c:\ then rename the directory c:\ocaml

To build Felix:

+ you need to open a cmd.exe window with MSVC++ configured to build Felix
+ run buildscript\win32setup.bat to setup both ocaml and felix from the Felix repository

For other uses of Ocaml you need to set your PATH to include c:\ocaml\bin and
OCAMLLIB to c:\ocaml\lib

(the win32setup.bat in Felix repo does this for you).
