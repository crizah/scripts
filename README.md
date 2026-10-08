scripts

- meow 
it copies shit from ur x11 clipboard into ur gnome terminal
use as:
```
meow # to auto paste whatever is on ur clipboard, auto gen name
meow name # to save as name, auto generates the extension
meow name.ext # change ext

put in one of ur bins, /usr/local/bin or ~/.local/bin (make sure ur bashrc has the export path to local bin)
```
- meowr
reverse of meow, copies from gnome terminal to ur x11 clipboard
use as:
```
meowr # copies the last modified file in curr dir
meowr <path> # copies the last modified files in the given path if its a dir
meowr <path> # copies the exact file
```
