# Compile the thesis from source

```bash
pdflatex -shell-escape main.tex; biber main; pdflatex -shell-escape main.tex; okular main.pdf
```