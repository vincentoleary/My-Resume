# my-cv

To convert my original CV from Markdown (easily readable on GitHub and GitHub pages) to other formats I use Pandoc. The original Markdown file is cv.md and contains some comments that hide longer sections. The file cv_comments_removed.md has these sections removed manually before being used to convert to a PDF.

For PDF conversion (Useful to share with others): pandoc -V geometry:margin=.75in cv_comments_removed.md -markdown -s -o cv.pdf

This CV and auto-generated PDF are both available here and used on my personal website hosted on GitHub.
