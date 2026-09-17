# Lecture 12: the dbar-Poincare lemma in one variable

A plain, black-and-white Beamer presentation with 29 slides. The introduction
recalls statements and references; the Fourier and one-variable arguments
include proofs.

- [Slides (PDF)](lecture-12.pdf)
- [Beamer source](lecture-12.tex)

## Contents

1. A one-slide reminder based on the `de-rham-dolbeault` notes: Dolbeault's
   theorem, exactness from Poincare, acyclicity of fine sheaves (Voisin 4.36),
   and the acyclic-resolution theorem (Voisin 4.32). Part 0 contains no proofs.
   Today's theorem and the next lecture's plan follow. Immediately after
   “Next lecture,” a slide compares Huybrechts 1.3.7, 1.3.8, and 1.3.9:
   one variable, several variables, then removal of the boundary-extension
   assumption for forms on an open polydisk.
2. Hilbert spaces and orthonormal expansions. The Fourier examples from
   `functional-analysis/functional-analysis.tex` are reproduced verbatim,
   including their proof. Completeness, normalized measures, the torus basis,
   and Fourier modes of forms follow separately.
3. Proof that `d` and `dbar` preserve frequencies.
4. Complex Cartan's formula, its eigenvalues on modes, primitives of nonzero
   modes, smooth convergence of the series, and constant cohomology representatives.
5. Embedding a disk in a large elliptic curve, extending its form with a cutoff,
   and removing the constant term with `dbar(bar z) = dbar z`.

The theorem is local: the disk proof assumes the form is smooth near its
closure. This suffices for exactness on stalks. Both `(0,1)` and `(1,1)` forms
are covered. The proofs use Stone-Weierstrass and the density of continuous
functions in `L^2` as standard background results.

## Build

With Beamer, Latin Modern, and `latexmk` installed:

```sh
cd lecture-12
make
```

Intermediate files go in `build/`. `make clean` removes them and keeps the
PDF in this directory.

## Sources and conventions

- Claire Voisin, *Hodge Theory and Complex Algebraic Geometry I*, Chapter 4:
  Definition 4.35 and Propositions 4.32 and 4.36.
  The numbering and statements follow the `de-rham-dolbeault` notes.

- Daniel Huybrechts, *Complex Geometry: An Introduction*,
  Propositions 1.3.7–1.3.8 and Corollary 1.3.9 (boundary-assumption comparison).
- Misha Verbitsky, Hodge theory, IMPA 2025:
  [Lecture 11](http://verbit.ru/IMPA/Kahler-2025/slides-Kahler-2025-11.pdf),
  [Lecture 12](http://verbit.ru/IMPA/Kahler-2025/slides-Kahler-2025-12.pdf),
  [Lecture 13](http://verbit.ru/IMPA/Kahler-2025/slides-Kahler-2025-13.pdf).
- [de-rham-dolbeault notes](../de-rham-dolbeault/de-rham-dolbeault.tex),
  as present in commit `610db25` of this repository.
- [Functional Analysis](https://github.com/danimalabares/functional-analysis/blob/main/functional-analysis/functional-analysis.tex),
  “Orthogonal projections,” lines 1031–1045 in the version read
  (Git blob `7fbf692c4d59594856090ef4e0bbea68eeb27022`). Slides 8–10 retain
  the examples' wording and formulas, including “the collection (or any subset
  thereof).” Frame breaks and formatting are added; the observation `m != n`
  is outside the quotation.

With `z = x + iy` and `I(partial_x) = partial_y`, the complex Cartan identity
for `dbar` uses `L_X + i L_IX`; the minus combination belongs to `partial`.
Both identities and their mode eigenvalues are displayed. The plus
combination has eigenvalue `in-m`, so the primitive coefficient is
`2 a_(n,m)/(in-m)`. Hartogs' theorem is stated with connected complement.
