# HUJI M.Sc. Thesis

This repository contains the LaTeX source code for the M.Sc. thesis at the Hebrew University of Jerusalem (HUJI). The document is structured as a book and includes all necessary components for a complete thesis.

## Project Structure

The project is organized as follows:

```
c:\Users\roymi\projects\MSc-Thesis
│
├── src/
│   ├── main.tex                # Main LaTeX file
│   ├── cover.tex               # Title page
│   ├── abstract.tex            # Abstract section
│   ├── acknowledgements.tex    # Acknowledgements section
│   ├── introduction.tex        # Introduction chapter
│   ├── scientific-background/
│   │   └── scientific_background.tex # Scientific background chapter
│   ├── motivation.tex          # Motivation chapter
│   ├── previous_work.tex       # Previous work chapter
│   ├── research_question.tex   # Research question chapter
│   ├── methods/
│   │   └── methods.tex         # Methods chapter
│   ├── results/
│   │   └── results.tex         # Results chapter
│   ├── conclusion.tex          # Conclusion chapter
│   └── thesis.bib              # Bibliography file
│
└── README.md                   # Project documentation
```

## Requirements

To compile the thesis, you need the following tools installed:

- **LaTeX Distribution**: Ensure you have a complete LaTeX distribution such as [TeX Live](https://www.tug.org/texlive/), [MiKTeX](https://miktex.org/), or [MacTeX](https://tug.org/mactex/).
- **Editor**: Any LaTeX editor like [Overleaf](https://www.overleaf.com/), [TeXworks](https://www.tug.org/texworks/), or [VS Code](https://code.visualstudio.com/) with the LaTeX Workshop extension.

## Compilation Instructions

1. Open the `main.tex` file in your LaTeX editor.
2. Compile the document using `pdflatex` (or your preferred LaTeX engine).
3. Ensure all references and citations are updated by running `pdflatex` multiple times if necessary.

Alternatively, you can use the command line:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

## Notes

- The `hyperref` and `bookmark` packages are included for hyperlinking and bookmarking in the PDF.
- The bibliography is managed using the `thesis.bib` file and the `apalike` style.

## Troubleshooting

If you encounter issues during compilation:

1. Ensure all required packages are installed in your LaTeX distribution.
2. Verify that the `main.tex` file specifies the correct LaTeX engine (`pdflatex`).
3. Check for missing or incorrectly referenced files (e.g., `cover.tex`, `thesis.bib`).

## License

This project is licensed for academic use. Please consult your institution's guidelines for thesis formatting and submission.

## Acknowledgements

Special thanks to the Hebrew University of Jerusalem for providing the template and resources for this thesis.
