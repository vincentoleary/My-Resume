# my-cv

To convert my original CV from Markdown (easily readable on GitHub) to other formats I use Pandoc.

For PDF (Useful to share with others): pandoc -V geometry:margin=1in cv.md -markdown -s -o cv.pdf

For HTML (Useful for my personal website): pandoc cv.md -markdown -t html -s -o cv.html
