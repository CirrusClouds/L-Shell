# L-Shell
Replace the shell with a CL REPL. Because I don't want to learn bash.

### Installation
Either run the script with it installed via quicklisp (recommended), or in-package from a CL REPL & run `repl` 

Tabs work by default if you use something like inferior-shell on emacs (not tested with others)
Paredit mode works beautifully

### Currently Implemented
- cd
- ls 
- cp
- substring searches
- directories showing in the input tab
- touch
- mkdir
- Direct bash commands output to string for useage
- All kinds of paths including relative and absolute
- Reflexive flags

### TODO
- Could we possibly get integration with emacs directory management
