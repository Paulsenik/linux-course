# Linux Grundkurs

Eine 6-7h Einführung in GNU/Linux mit KDE Plasma als Desktopumgebung.

[Kurs PDF](out/linux-kurs.pdf)

## Install

```bash
sudo apt install texlive-latex-recommended texlive-pictures
```

## Build Latex

Add/Remove `handout`-value from `\documentclass[handout]` for rendering without animations.

Simple Build:
```bash
pdflatex linux-kurs.tex
```

(*auch: TeX-Editor oder IDE-Plugin benutzen*)

### Theme
[Metropolis-Theme](https://github.com/matze/mtheme)
