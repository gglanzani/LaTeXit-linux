LaTeXit-linux
=============

When you want to include LaTeX code in programs like Inkscape, in Mac OS X
there is this great program called LaTeXit which let’s you input LaTeX code,
and then it outputs a pdf, as big as needed, not a whole page, which you can
easily embed. In Linux there is nothing like this. So I created a little script
which does the same on linux, only the output is a .ps file.

## How to use it

Write in the terminal

```bash
latexit "latex code like x^2 or whatever"
```

A file called `output.ps` will be created in the directory where you issued the
command. Nothing more is needed, just drag the file to Inkscape and trash it
when you don’t need it anymore!



