# Kodaira lectures

The original nine-slide outline is preserved unchanged in [plan/slides.tex](plan/slides.tex).

| Folder | Draft | Slides |
| --- | --- | ---: |
| [lecture-23](lecture-23/slides.tex) | Nadel vanishing | 22 |
| [lecture-24](lecture-24/slides.tex) | Kodaira embedding and Kawamata–Viehweg | 25 |

These shorter drafts follow Daniel's talk checklist: announce the destination, explain the route, carry out the argument, and return to the result. They retain the dbar-poincare Beamer style, use mathematical pictures and short historical pauses, and move longer technical arguments into optional preparation notes. Shared styling is in [preamble.tex](preamble.tex).

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

Lecture 23 focuses on the multiplier ideal, the weighted Dolbeault resolution, and the Nadel deduction. Bochner–Kodaira and Kodaira vanishing are brief reminders. The weighted local lemma and singular-weight L2 existence theorem remain explicit analytic inputs. Hahn–Banach, operator domains, and approximation details are optional notes.

Lecture 24 proves embedding using values and first jets, then proves the line-bundle version of Kawamata–Viehweg using a fixed effective divisor and an N-th-root metric. The auxiliary growth and local-integrability proofs are in the notes.

See [lecture-23/notes.md](lecture-23/notes.md), [lecture-24/notes.md](lecture-24/notes.md), and [sources.md](sources.md). Each notes file starts with the essential preparation, followed by optional details. No “Earlier inputs” footers have been restored. Numbered references to our seminar retain the known speaker's name.

Talk preparation checklist: [HOW TO GIVE A TALK](https://github.com/danimalabares/archive/blob/main/archive/HOW_TO_GIVE_A_TALK.txt), saved verbatim from Daniel.
