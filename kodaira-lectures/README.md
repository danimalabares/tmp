# Kodaira lectures

Six Beamer slides, restarted at Daniel's request on 2026-11-01:

1. Nadel vanishing theorem.
2. Kodaira vanishing theorem.
3. Kodaira vanishing: proof steps.
4. Nadel vanishing: proof steps.
5. Kodaira embedding theorem.
6. Kodaira embedding: proof steps via Nadel.

No cover or appendix. The earlier 27-slide draft remains only in Git history.

## Build

```sh
pdflatex -interaction=nonstopmode -halt-on-error slides.tex
pdflatex -interaction=nonstopmode -halt-on-error slides.tex
```

Open `slides.pdf`. Requires Beamer, Latin Modern and AMS packages.
Generated PDFs and auxiliary files are ignored.

## Scope and sources

The proof slides are outlines, not full proofs. Local/global weighted L2 solvability and the construction of singular metrics with uniform powers still require explanation.

Source map from the previously inspected [Verbitsky 2025 course notes](http://verbit.ru/IMPA/Kahler-2025/): lecture 16, slides 4–5; lecture 23, slides 2–4 and 5–12; lecture 24, slides 6–12. The smooth argument also follows [HP complex-geometry.tex](https://github.com/danimalabares/heap-project/blob/017bd8e32692d9d16ec324f757193cf857875df9/complex-geometry.tex).

The assignment is the last two course lectures. Lecture 24 also includes Kawamata–Viehweg vanishing, not yet included in this six-slide deck. Earlier Hilbert-space, L2, pseudoconvexity and plurisubharmonic-function material provides the analytic prerequisites for Nadel. Kodaira vanishing is a recap of earlier material.

Created and revised with ChatGPT.
