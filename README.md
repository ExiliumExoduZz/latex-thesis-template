# latex-thesis-template
LaTeX template for an thesis @ FHDW Bergisch Gladbach

In Progress:

- [ ] Mehr Quellenverzeichnisse
- [ ] Header Korrekturen

## Compile
Bitte verwendet XeLaTeX als Compiler, sodass die Fonts richtig angezeigt und genutzt werden können.
Ebenfalls notwendig sind die Befehle "makeindex" und "bibtex", um das Index zu generieren und das Quellenverzeichnis.

```
xelatex thesis
makeglossaries thesis
xelatex thesis
xelatex thesis
biber thesis
makeindex thesis
xelatex thesis
xelatex thesis
```

## Customzation
Innerhalb des "configuration" Ordners kann innerhalb der CustomProperties.tex Datei die eigene Anpassung vorgenommen werden.