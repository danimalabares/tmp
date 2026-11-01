# Kodaira lectures

Ten Beamer slides, restarted and expanded at Daniel's request on 2026-11-01:

1. Nadel vanishing theorem.
2. Kodaira vanishing theorem.
3. Kodaira vanishing: proof steps.
4. Nadel vanishing: proof steps.
5. Kodaira embedding theorem.
6. Kodaira embedding: proof steps via Nadel.
7. Nef and big line bundles (projective setting).
8. Kawamata–Viehweg vanishing theorem.
9–10. Kawamata–Viehweg proof steps, with explicit inputs.

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

Source map from the previously inspected [Verbitsky 2025 course notes](http://verbit.ru/IMPA/Kahler-2025/): lecture 16, slides 4–5; lecture 23, slides 2–4 and 5–12; lecture 24, slides 4 and 6–16; lecture 22, slides 11–12 (Poincaré–Lelong). The smooth argument also follows [HP complex-geometry.tex](https://github.com/danimalabares/heap-project/blob/017bd8e32692d9d16ec324f757193cf857875df9/complex-geometry.tex).

The assignment is the last two course lectures. The deck now includes the Kawamata–Viehweg statement and proof outline from lecture 24. Earlier Hilbert-space, L2, pseudoconvexity and plurisubharmonic-function material provides the analytic prerequisites for Nadel. Kodaira vanishing is a recap of earlier material.

Created and revised with ChatGPT.

## Details still to develop

The outline covers the main endpoint theorems of lectures 23–24. The substantive details to explain are the multiplier-ideal integrals (maximal ideal, its square, mild divisor weights), the weighted local Dolbeault lemma and fine resolution, the construction of positive currents with prescribed singularities, the uniform power in embedding, and the section-growth/restriction argument in Kawamata–Viehweg. Coherence of multiplier ideals is stated but explicitly not used by Misha. Blow-up remarks are supplementary to this route.

Course PDFs were checked from Daniel's uploaded `Kahler-2025 2(1).zip`. Numerical nefness is stated only in the projective setting. In the metric construction, curvature is normalized by i/(2 pi), and the divisor D stays fixed as N increases. The phrase 'multiplier ideal vanishes' in Misha's slides is rendered as I_h = O_X.
