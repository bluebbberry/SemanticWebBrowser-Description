How to generate document:

Create out-folder if not present.

Then execute:

```bash
pdflatex -output-directory=out main.tex
biber -output-directory=out main
pdflatex -output-directory=out main.tex
```
