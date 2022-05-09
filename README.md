# gateway-whitepaper
Gateway Protocol Whitepaper

# Building
A pdf document can be build with `pdflatex` or `lualatex`.

# Image Conversion
Some diagrams are generated via [PlantUML](https://plantuml.com/), to allow for a simple update mechanism.
Since PlantUML only generates lossless images as SVG, one needs to convert those into a format that LaTeX supports.

e.g. via `inkscape`:
```bash
inkscape figures/03-pass-state-diagram.svg --export-area-drawing --batch-process --export-type=pdf --export-filename=figures/03-pass-state-diagram.pdf
```
