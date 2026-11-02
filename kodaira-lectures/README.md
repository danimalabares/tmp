# Kodaira lectures

The original nine-slide outline is preserved unchanged in [plan/slides.tex](plan/slides.tex).

| Folder | Draft | Slides |
| --- | --- | ---: |
| [lecture-23](lecture-23/slides.tex) | From curvature to Nadel vanishing | 41 |
| [lecture-24](lecture-24/slides.tex) | Kodaira embedding and Kawamata–Viehweg | 43 |

These are full first drafts, modelled on the 36- and 51-frame `dbar-poincare` lectures: the same 16:9 Beamer format, serif typography, white background, generous space, and short steps in calculations. Shared styling is in [preamble.tex](preamble.tex). Mathematical pictures are editable TikZ; the Dolbeault portrait is reused from the existing repository.

## Build

Run from this folder:

```sh
make
```

Or compile an individual deck from its own folder:

```sh
cd lecture-23
pdflatex -interaction=nonstopmode -halt-on-error slides.tex
pdflatex -interaction=nonstopmode -halt-on-error slides.tex
```

Use `lecture-24` or `plan` in place of `lecture-23` for the other decks. Compiled PDFs remain local, following the repository's existing PDF ignore rule.

## Mathematical scope

Lecture 23 builds the multiplier ideal, recalls Bochner–Kodaira and Kodaira vanishing, constructs the weighted Dolbeault resolution, explains the functional analysis behind solvability, and derives Nadel from the singular-weight L2 existence theorem. The last theorem and the weighted local lemma are **explicit analytic inputs**, with a proof mechanism explained; their full regularization/domain proofs are not claimed here.

Lecture 24 gives the logarithmic-cutoff construction for embedding, including one exponent valid for all points and pairs, then constructs the mild divisor metric for Kawamata–Viehweg. It includes nef/big definitions, a blowup example, the dimension count, Poincaré–Lelong, and the small-exponent integrability argument.

See [lecture-23/notes.md](lecture-23/notes.md), [lecture-24/notes.md](lecture-24/notes.md), and [sources.md](sources.md). Historical remarks are sourced there. No “Earlier inputs” footers have been restored. Numbered references to our seminar retain the known speaker's name.

Talk preparation checklist: [HOW TO GIVE A TALK](https://github.com/danimalabares/archive/blob/main/archive/HOW_TO_GIVE_A_TALK.txt), saved verbatim from Daniel.
