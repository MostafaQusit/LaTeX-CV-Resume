# Professional LaTeX CV/Resume Template

[![LaTeX](https://img.shields.io/badge/Made%20with-LaTeX-1f425f.svg)](https://www.latex-project.org/)

A modern, ATS-friendly LaTeX template for CV and Resume, featuring:

- Clean typography with Charter font
- Responsive layout
- Hyperlink integration
- Skills matrix visualization
- Project highlights section
- Automated PDF metadata for ATS systems

## Features

✨ Dual version support (Detailed CV + Concise Resume)  
📄 ATS-optimized formatting  
🎨 Consistent styling across documents  
🔗 Interactive elements (tooltips, hyperlinks)  
📱 Mobile-friendly layout  
✈️ Aviation-specific section enhancements  

## Getting Started

1. **Clone Repository**

   ```bash
   git clone https://github.com/MostafaQusit/LaTeX-Resume.git
   ```

2. **Compile Documents**

   ```bash
   pdflatex CV.tex
   pdflatex Resume.tex
   ```

3. **Customize Content**
   - Update personal information in `HEADING` section
   - Modify experience/project entries
   - Adjust skill matrix in `SKILLS` section

## Customization Guide

### Change Font

Uncomment preferred font in preamble:

```latex
% sans-serif options:
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}

% serif options:
% \usepackage{CormorantGaramond}
```

### Modify Color Scheme

Add this to preamble (replace `PrimaryColor`):

```latex
\usepackage{xcolor}
\definecolor{PrimaryColor}{RGB}{0, 102, 204}
```


### Add Section

Use existing section templates:

```latex
\section{New Section}
  \resumeSubHeadingListStart
    \resumeSubItem{Item 1}
    \resumeSubItem{Item 2}
  \resumeSubHeadingListEnd
```

## Contact

Mostafa Qusit - [LinkedIn](https://linkedin.com/in/mostafa-qusit) - [Email](mailto:mostafahmedqusit@gmail.com)

Project Link: [https://github.com/MostafaQusit/LaTeX-Resume](https://github.com/MostafaQusit/LaTeX-CV-Resume)
