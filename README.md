econ-w3213-recitation-notes
===========================

Recitation Notes for Intermediate Macroeconomics

Pretty self explanatory. LaTeX dependencies are listed in the .tex files themselves.

## How To Download

If you're not familiar with GitHub or computers in general, follow these steps

1. Click on "Download ZIP" on the right
2. Extract the ZIP file
3. Use the PDF files in the folder and ignore the `.tex` files

## Files Included

Recitation notes are in the folder itself, named numerically. For example

- `00 Mathematics Crash Course.pdf`
- `01 Production.pdf`

The `.tex` files are LaTeX files used to compile the PDFs.

There should also be a folder called `Student Answers`. Those are answers to questions that people ask (over email or anything). I find it too cumbersome to type math equations in email, so I usually send them a document like this. Much neater and faster.

## Dependencies

If you're interested in compiling the LaTeX files itself, here's what you need

- `dominatrix` by @kenlimmj. Excellent LaTeX drop-in package that solves most of the problems you'll ever have
- TexLive 2013 and above, with `pgfplot` updated to the latest version. Otherwise, the compiler throws errors for the `tikzpicture` graphs.

That's really all. `dominatrix` forces you to compile using XeTeX in case you insist on doing otherwise.