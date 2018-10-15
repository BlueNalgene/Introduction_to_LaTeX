# Introduction_to_LaTeX

## What is covered?

This is an introduction to LaTeX presentation created in LaTeX.  This covers the basics of:

- What is LaTeX?
- The parts of a simple document
- Editors
- Important tools and packages (e.g. geometry, tables, graphics, floats, equations, itemize/enumerate, bibliography)
- Examples only of advanced tools (e.g. custom classes, TikZ, microtype)
- Contact information for members of the University of Oklahoma Library experts and the author.

## Who is it for?

This presentation is about 45-60 minutes in length and is intended to just touch on the basics and
make users aware of features they may not have been exposed to.  Thus, it is recommended for beginners.

Intermediate users are offered the original material for the slides as examples.  Since all of the presentation was written
in LaTeX, it makes it possible to use this as a source of examples of the material covered.  Users are encouraged to play 
and break things to learn by doing.

## Reported Issues

The structure of the document relies on writing several examples from "examplepages.tex" in a very inefficient manner.
The method used requires use of the ``\write18`` function.  This is a potentially dangerous command, as it allows the code
to execute code on the computer's shell.  It is used in this presentation code to compile individual pages as minimal examples.

Many IDE's do not allow compilation of code with this command.  

## Build

### In a Terminal

```
git clone https://github.com/BlueNalgene/Introduction_to_LaTeX.git
cd Introduction_to_LaTeX
pdflatex -synctex=1 -shell-escape -interaction=nonstopmode Introduction_to_LaTeX.tex
```

### In Overleaf

Times out in Overleaf, don't bother

## Presentation History

Materials originally presented at OU Resbaz 2018.

## Can I steal from this?

Please steal this content.  I prefer if you cite me so I get credit and contact me so I get warm fuzzies, but no pressure
or obligation to do so.  Free as in free.
