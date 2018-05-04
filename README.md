# win64 ocaml binary
Felix now requires Ocaml 4.06. 

To fetch the binary on Windows I created a workspace and opened a CMD.EXE console and typed:
```
git clone -b ocaml-4.06.0 --depth 1 https://github.com/felix-lang/win64ocaml.git
```
Of course you need git installed for this to work. Now you need to copy Ocaml
to the location for which it was built, namely:
```
C:\ocaml
```
The easiest way to do this is with the GUI file explorer.
