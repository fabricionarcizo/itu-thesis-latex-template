# ITU Thesis LaTeX Template

This repository provides a LaTeX template for creating a thesis following the formatting guidelines of [IT University of Copenhagen (ITU)](https://itu.dk). The template is designed to be modular, customizable, and easy to use, making it suitable for students writing their bachelor's, master's, or Ph.D. theses.

## Features

- **Compliant with ITU formatting standards**
- Modular file structure for easy organization
- Predefined styles for chapters, appendices, and sections
- Support for bibliography management with BibTeX
- Includes templates for:
  - Tables and figures
  - TikZ diagrams and PGF plots
  - Appendices and annexes
- Sample data, images, and code files for demonstration
- Customizable `.sty` and `.cls` files for advanced users

## Directory Structure

```plaintext
itu-thesis-latex-template/
│
├── main.tex            # Main LaTeX source file
├── references.bib      # Bibliography file
├── LICENSE             # License for the repository
├── ITU.sty             # ITU thesis style file
├── abnt.cls            # Additional LaTeX class file
│
├── chapters/           # Individual chapter files
├── appendices/         # Appendix files
├── images/             # Images and illustrations
├── tables/             # Tables included in the thesis
├── codes/              # Code files for inclusion
├── data/               # Datasets used in the thesis
├── style/              # Additional LaTeX styles
├── annexes/            # Annexes for supplementary materials
├── tikz/               # TikZ diagrams
├── pgf/                # PGF plots
│
├── .gitignore          # Git ignore file
└── README.md           # Project documentation
```

## Getting Started

### Prerequisites

Ensure you have the following software installed:

- **LaTeX Distribution**: [TeX Live](https://www.tug.org/texlive/), [MikTeX](https://miktex.org/), or [MacTeX](https://tug.org/mactex/)
- **PDF Viewer**: Any PDF reader to view compiled files

### Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/fabricionarcizo/itu-thesis-latex-template.git
   cd itu-thesis-latex-template
   ```
2. Open `main.tex` in your preferred LaTeX editor (e.g., Overleaf, Texmaker, TeXworks).

### Compilation

Run the following command to compile the thesis:

```bash
pdflatex main.tex
bibtex thesis
makeglossaries thesis
pdflatex main.tex
pdflatex main.tex
```

Alternatively, use an integrated LaTeX editor like Overleaf or Texmaker.

## Usage

1. Edit the `main.tex` file to include your thesis title, author information, and abstract.
2. Write individual chapters in separate files under the `chapters/` directory and include them in `main.tex` using `\include`.
3. Add your figures to the `images/` directory and include them using the `\includegraphics` command.
4. Manage references in the `references.bib` file.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- The LaTeX community for tools and inspiration.
- All contributors who helped enhance this template.

---

For issues or suggestions, please open an [issue](https://github.com/fabricionarcizo/itu-thesis-latex-template/issues).
