# my-cv

To convert my original CV from Markdown (easily readable on GitHub and GitHub pages) to other formats I use Pandoc. The original Markdown file is cv.md. The file resume.md has some abbreviated sections to fit within 2 pages.

For PDF conversion (Useful to share with others): pandoc -V geometry:margin=.75in resume.md -markdown -s -o resume.pdf

This CV and auto-generated PDF are both available here and used on my personal website hosted on GitHub.
