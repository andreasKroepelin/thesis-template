# Thesis template

This is a template for writing a thesis with LaTeX.
It uses modern features and therefore **must be used with LuaLaTeX**.

### Fonts
This template suggests using certain fonts to improve your document's appearance over the standard LaTeX look.
Follow the links in the code to download them and then install them according to the procedure required by your operating system.

### Output directory
It is recommended to create an output directory to keep your workspace clean.
You can make `lualatex` write to it by calling `lualatex --output-dir=[name of dir] thesis.tex`.
If you are using the package `minted` for syntax highlighting, make sure to declare `\usepackage[outputdir=...]{minted}`.
