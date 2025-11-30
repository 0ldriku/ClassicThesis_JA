# ClassicThesis Template (Enhanced for Japanese/CJK Support)

A modified version of the Classic Thesis Style template with enhanced support for Japanese and multilingual academic writing.

## About This Template

This template is based on [ClassicThesis v4.8](https://ctan.org/pkg/classicthesis) by André Miede and Ivo Pletikosić, with customizations for academic research writing, particularly for Japanese and multilingual documents.

### Key Features

- **APA 7th Edition Citation Style**: Configured for proper academic citations
- **Enhanced Japanese Support**: Optimized for XeLaTeX with CJK font support
- **Japanese Name Formatting**: Custom delimiter (・) between multiple Japanese authors
- **Japanese Reference Sorting**: Proper bibliographic ordering using the 50-on table
- **Multi-language Support**: Built-in support for Japanese, Simplified Chinese, Traditional Chinese, and Korean


## ⚡ Quick Start (TL;DR)

Get started with **Overleaf** in less than a minute:

1.  **Download:** Click the green **Code** button (top of this page) and select **Download ZIP**.
2.  **Upload:** In Overleaf, click **New Project** $\rightarrow$ **Upload Project**, then upload the ZIP file.
3.  **Configure:** Inside the editor, click **Menu** (top left icon) and set the **Compiler** to **XeLaTeX**.
4.  **Run:** Click **Recompile**. You are ready to write!

## Usage

### Compilation

This template is designed to work with **XeLaTeX** for best Japanese/CJK language support:

This template works on Overleaf. Simply open the Menu (top left) and set the Compiler to XeLaTeX.

For local compilation:

```bash
xelatex ClassicThesis.tex
biber ClassicThesis
xelatex ClassicThesis.tex
xelatex ClassicThesis.tex
```

For English-heavy documents with minimal Japanese, you can use pdfLaTeX (see Chapter 1 in the compiled PDF for details).

### Getting Started

1. Main document: `ClassicThesis.tex`
2. Configuration: `classicthesis-config.tex`
3. Chapters: `Chapters/Chapter01.tex`, `Chapter02.tex`, etc.
4. Bibliography: `Bibliography.bib`, `part1.bib`, `part2.bib`, etc.

See the compiled PDF documentation for detailed usage instructions and examples.


## License

This modified template is distributed under the **GNU General Public License v2 or later**, the same license as the original ClassicThesis.

### Original Work

- **ClassicThesis** by André Miede and Ivo Pletikosić
- Original template: https://ctan.org/pkg/classicthesis
- If you appreciate the original style, the authors welcome postcards: http://postcards.miede.de

### Important Note

The GPL license applies to the template files themselves (.tex, .sty, etc.). **Documents you create using this template** (your thesis, dissertation, etc.) are **not** affected by the GPL and can be licensed however you wish.

## Acknowledgments

This template builds upon the excellent work of André Miede and Ivo Pletikosić. The enhancements focus on supporting Japanese academic writing needs while maintaining the elegant design principles of the original ClassicThesis style.
