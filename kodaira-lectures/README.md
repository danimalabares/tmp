# Kodaira lectures — discussion deck

A 27-slide editable Beamer draft following our discussion, from the section-separation problem to the smooth Bochner–Kodaira proof and the statement of Nadel vanishing.

## Build

From this folder, run:

```sh
pdflatex -interaction=nonstopmode -halt-on-error slides.tex
pdflatex -interaction=nonstopmode -halt-on-error slides.tex
```

Open `slides.pdf`. Requires a TeX installation with Beamer, Latin Modern and AMS packages. The repository ignores generated PDFs and auxiliary files.

## Scope

- Slides 2–6: projective maps, values and jets, the exact sequence, and the H1 obstruction.
- Slides 7–10: singular metrics and multiplier ideals, with explicit integrability calculations.
- Slides 11–20: line-bundle curvature, the connection squared, the full Bochner–Kodaira calculation, the curvature bound and smooth Kodaira vanishing.
- Slides 21–25: what the smooth theorem does not yet supply; Nadel's statement; the canonical-bundle twist; the weighted Dolbeault complex and remaining proof obligations.
- Slide 26: Kodaira–Nakano as an appendix.
- Slide 27: source map.

The Kähler identities and smooth elliptic Hodge theory are prerequisites. The singular L2 existence theorem, the resolution by weighted forms, and the global construction of singular metrics are explicitly left to prove. Kawamata–Viehweg vanishing is not covered yet. This is a record of the discussion, not a complete replacement for course lectures 23 and 24.

## Sources

[Misha Verbitsky, Kähler geometry, IMPA 2025](http://verbit.ru/IMPA/Kahler-2025/):

- Lecture 16, slides 4–5: Hodge theory and Bochner–Kodaira.
- Lecture 23, slides 2–4 and 12: singular metrics, integrability examples and Nadel.
- Lecture 24, slides 10–12: ideal vanishing and Kodaira embedding.

The smooth proof follows the discussion also recorded in [heap-project/complex-geometry.tex](https://github.com/danimalabares/heap-project/blob/017bd8e32692d9d16ec324f757193cf857875df9/complex-geometry.tex).

## Conventions and checks

For a local frame with squared norm `exp(-psi)`, curvature is `Theta = partial barpartial psi`. The multiplier-ideal weight is written `exp(-2 phi)`, so `psi = 2 phi`. All norms in the smooth energy argument are the global L2 norms. The curvature commutator acts on basis monomials, not scalar coefficients.

Created with ChatGPT. Compiled with pdfLaTeX and visually reviewed; the smooth and singular proof statuses are deliberately distinguished.
