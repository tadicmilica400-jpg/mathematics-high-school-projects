# Secondary-School Mathematics Seminar Papers

## Overview and academic context

This repository contains two seminar papers written in Serbian while I attended the Mathematical Grammar School in Belgrade. They are **secondary-school academic work**, not peer-reviewed publications or original research papers.

The repository preserves both the LaTeX source and compiled PDF for each paper. The work demonstrates early engagement with proof-based mathematical analysis, formal definitions and technical typesetting.

## Papers

### Convergence of Sequences

The paper introduces real sequences and develops:

- boundedness and monotonicity;
- epsilon-based definitions of limits and convergence;
- divergent and null sequences;
- algebraic and asymptotic properties of convergent sequences;
- theorem-proof and worked-example presentation.

- [Compiled paper (Serbian)](sequence-convergence/sequence-convergence.pdf)
- [LaTeX source](sequence-convergence/main.tex)

### Taylor's Formula and Taylor Series

The paper studies polynomial approximation through:

- Taylor polynomials and remainders;
- Rolle's theorem and Cauchy's mean value theorem;
- Lagrange and Cauchy remainder forms;
- Taylor's theorem and Taylor series;
- examples for exponential, cosine and logarithmic functions.

- [Compiled paper (Serbian)](taylor-formula-and-series/taylor-formula-and-series.pdf)
- [LaTeX source](taylor-formula-and-series/main.tex)

## Sources and language

Both papers are written in Serbian and include bibliographic references in their source files. Mathematical terminology in this README is translated for accessibility; the papers themselves remain in their original language.

## Building the documents

From either paper directory, with a LaTeX distribution that provides the declared Serbian/Cyrillic language and font packages:

```bash
pdflatex main.tex
pdflatex main.tex
```

The second pass resolves cross-references. Compilation could not be independently repeated during this audit because a LaTeX distribution was unavailable; the committed PDFs are therefore the immediately reproducible reading artefacts.

## Repository structure

```text
sequence-convergence/
  main.tex
  sequence-convergence.pdf
taylor-formula-and-series/
  main.tex
  taylor-formula-and-series.pdf
```

## Limitations

- The papers reflect secondary-school coursework and should be evaluated in that context.
- They have not been translated into English or independently peer reviewed.
- The repository does not claim novelty beyond the exposition, proofs and examples assembled for the seminar assignments.

## Author

Milica V. Tadić  
Mathematical Grammar School, Belgrade


