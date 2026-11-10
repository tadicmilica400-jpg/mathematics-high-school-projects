# Mathematics Projects from High School

This repository contains two seminar papers I wrote while attending the Mathematical Grammar School in Belgrade. The papers are written in Serbian and focus on foundational topics in mathematical analysis. Both the original LaTeX source files and compiled PDF versions are included.

## Projects

### Sequence Convergence

An introduction to real sequences and their asymptotic behaviour, including:

- bounded and monotone sequences;
- convergence and limits;
- divergent and zero sequences;
- fundamental properties of convergent sequences, with proofs and examples.

- [Read the PDF](sequence-convergence/sequence-convergence.pdf)
- [View the LaTeX source](sequence-convergence/main.tex)

### Taylor's Formula and Taylor Series

A study of polynomial approximation and Taylor expansions, including:

- Taylor polynomials and remainders;
- Rolle's theorem and Cauchy's mean value theorem;
- Lagrange and Cauchy forms of the remainder;
- Taylor's theorem and Taylor series;
- examples involving the exponential, cosine, and logarithm functions.

- [Read the PDF](taylor-formula-and-series/taylor-formula-and-series.pdf)
- [View the LaTeX source](taylor-formula-and-series/main.tex)

## Building the Documents

Each paper can be compiled from its project directory with a standard LaTeX installation:

```bash
pdflatex main.tex
pdflatex main.tex
```

Running the command twice resolves cross-references. The source uses Serbian language and Cyrillic font support provided by the LaTeX packages declared in each document.

## Author

Milica V. Tadić  
Mathematical Grammar School, Belgrade

