# Minimalist LaTeX Template for Academic Presentations

This repository contains a LaTeX template for academic presentations. The template carefully follows typographical best practices and has a minimalist design.

## Documentation

The template's documentation is available at https://pascalmichaillat.org/d1/.

## Features

+ The font for text, roman math, and numbers is [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro).
+ The font for Greek and calligraphic math is [Euler](http://luc.devroye.org/fonts-26139.html).
+ No colors are used in the text (only black/gray) to reduce distraction. 
+ Colors are reserved for graphs and alerts.
+ Margins, spacing, and font size are set for comfortable reading.
+ There are no frills at the periphery of the slides.

## Usage

+ Clone the repository to your local machine.
+ Start editing the LaTeX file `presentation.tex` to replace the boilerplate content with the content of your presentation. 
+ Replace the figures in the PDF file `figures.pdf` with the figures that will be included in the presentation. There should be one figure per page.
+ Compile `presentation.tex` with pdfTeX. This will generate a new PDF file named `presentation.pdf`.
+ The LaTeX style file `presentation.sty` collects all the commands to format the presentation. The file must be included in the same folder as `presentation.tex`. It can be modified to alter the presentation's format.
+ The file `presentation.pdf` is not required to use the template. It only illustrate the output of the template, and will be overridden once `presentation.tex` is compiled.

## Software

The template was developed on a Mac running macOS Ventura 13.2 with the MacTeX-2021 distribution. Hopefully, it should also work on other machines and with more recent distributions.

## License

The content of this repository is licensed under the terms of the MIT License.

## Related resources

+ [LaTeX template for academic papers](https://github.com/pmichaillat/latex-paper) – This template produces academic papers following the same principles, and with a similar appearance, as this presentation template. 
+ [LaTeX commands to write math](https://github.com/pmichaillat/latex-math) – These commands make it easy to write mathematical expressions. They can be used in combination with this paper template.
