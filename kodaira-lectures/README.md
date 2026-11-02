# Kodaira lectures

Five Beamer slides, restructured at Daniel's request:

1. Title.
2. Bochner–Kodaira identity and proof.
3. Kodaira vanishing and proof.
4. Nadel vanishing and proof using weighted L2 solvability.
5. Kawamata–Viehweg vanishing and proof.

Earlier versions remain in Git history. Kodaira embedding is omitted from the current requested structure.

## Build

```sh
pdflatex -interaction=nonstopmode -halt-on-error slides.tex
pdflatex -interaction=nonstopmode -halt-on-error slides.tex
```

Generated PDFs and auxiliary files are ignored.

## Sources and proof scope

Based on the uploaded Misha Verbitsky 2025 course slides and HP complex-geometry.tex. Source references are in TeX comments and prerequisite labels on the slides: lecture 16 for Bochner–Kodaira and smooth vanishing; lecture 23 for Nadel; lecture 24, slides 4 and 13–16, for Kawamata–Viehweg; lecture 22 for Poincaré–Lelong.

These are compact proofs with explicit inputs. The Nadel slide invokes the local weighted Dolbeault lemma and global singular L2 existence theorem; those analytic inputs still require explanation in the lectures. The KV slide invokes the section-growth estimate, small-exponent integrability and nef-plus-ample positivity. It retains the requested weaker-positivity sentence and includes the nef and big definitions.

Created and revised with ChatGPT.
