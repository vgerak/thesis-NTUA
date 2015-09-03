thesis
======
* [About](#about)
* [Fonts / Styles](#fonts--styles)
* [How-to](#how-to)

## About ##

This is the diploma thesis that I submitted on September 2nd, 2015
to fulfil the requirements for the Engineering Diploma in the
School of Electrical and Computer Engineering of National Technical University
of Athens.

## Fonts / Styles ##
Fonts for the dissertation are defined in the softlab-thesis.cls file.

**Roman font**:	Linux Libertine O

**Sans font**: Linux Biolinum O

**Monospace font**: Linux Libertine Mono O

The [Beamer2Thesis](http://ftp.ntua.gr/mirror/ctan/macros/latex/contrib/beamer-contrib/themes/beamer2thesis/doc/basic_guide/beamer2thesis.pdf) theme has been used for the presentation, with some modifications. You can find the .sty files that were used in the Presentation/Styles folder.

## How-to ##

Provided you have installed LaTeX as well as the `latexmk` tool, you can do:

```
make
```

in the corresponding folder and a `thesis.pdf` file will be created.

If you want to remove the helper files, you can do:

```
make clean
```