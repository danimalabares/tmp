# Kodaira lectures

Nine Beamer slides, following Daniel's clarified structure:

1. Title.
2. Bochner–Kodaira identity.
3. Bochner–Kodaira proof (numbered list).
4. Kodaira vanishing theorem.
5. Kodaira vanishing proof (numbered list).
6. Nadel vanishing theorem.
7. Nadel proof (numbered list).
8. Kawamata–Viehweg vanishing theorem.
9. Kawamata–Viehweg proof (numbered list).

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
