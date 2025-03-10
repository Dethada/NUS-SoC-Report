# NUS SoC UROP LaTeX Template

LaTeX template for NUS SoC UROP/FYP final report.
Made based on
- [NUS SoC UROP report format guidelines](https://www.comp.nus.edu.sg/wp-content/uploads/2023/10/UROP_Report_Format.pdf).
- [NUS SoC FYP report format
guidelines](https://www.comp.nus.edu.sg/wp-content/uploads/2023/10/FYP-Report-Format-final_000.pdf)

Sample report can be found [here](sample/sample.pdf).

To compile the pdf (this will automatically compile the pdf whenever the source files are modified):
```bash
latexmk -pdf -outdir=build -pvc main.tex
```

To modify the Project Type (UROP or FYP), Project Title, Author Name and Academic Year, modify the
last few lines of [preamble.tex](preamble.tex)

```latex
% \newcommand{\projecttype}{B.Comp. Dissertation}
\newcommand{\projecttype}{Undergraduate Research Opportunity Programme (UROP) Project Report}
\newcommand{\authorname}{John Doe}
\newcommand{\projecttitle}{Project Title}
\newcommand{\academicyear}{2024/2025}
```
