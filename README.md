# my-cv

This CV and auto-generated PDF are both available here and used on my personal website also hosted on GitHub.

I convert my CV from markdown (easily readable on GitHub and GitHub pages) to other formats using the program Pandoc. The original markdown file is cv.md. The other file resume.md has some sections shortened to fit within 2 pages. Both files contain YAML metadata in order to add page numbers and a header title to the final PDF. The section for my contact information contains raw LaTeX code to add rich icons in the PDF, but this is also removed for the markdown files shared on my website.

For PDF conversion of resume: pandoc -V geometry:textwidth=504pt -V geometry:textheight=660pt -V geometry:top=72pt resume.md -markdown -s -o resume.pdf
