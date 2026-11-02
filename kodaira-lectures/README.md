# Kodaira lectures

The original nine-slide outline is preserved unchanged in [plan/slides.tex](plan/slides.tex).

| Folder | Draft | Slides |
| --- | --- | ---: |
| [lecture-23](lecture-23/slides.tex) | Embedding mechanism and Nadel vanishing | 28 |
| [lecture-24](lecture-24/slides.tex) | Metric construction and Kawamata–Viehweg | 20 |

These two decks form one continuous argument, with a short course recap and Kodaira embedding as the initial goal. The first lecture explains how H1-vanishing gives values and first jets before developing Nadel. The second resumes with the missing metric construction. They follow Daniel's talk checklist: announce the destination, explain the route, carry out the argument, and return to the result. They retain the dbar-poincare Beamer style, use mathematical pictures and short historical pauses, and move longer technical arguments into optional preparation notes. Shared styling is in [preamble.tex](preamble.tex).

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

Lecture 23 opens with two recap slides covering the course from complex structures to singular psh weights. It then states Kodaira embedding, explains why point and tangent separation suffice, and proves the mechanism from the evaluation exact sequence. This motivates the multiplier ideal, the weighted Dolbeault resolution, and the Nadel deduction. Bochner–Kodaira and Kodaira vanishing are brief reminders. The weighted local lemma and singular-weight L2 existence theorem remain explicit analytic inputs. Hahn–Banach, operator domains, and approximation details are optional notes.

Lecture 24 constructs the metrics required by the first lecture, concludes embedding without repeating the section-separation argument, then proves the line-bundle version of Kawamata–Viehweg using a fixed effective divisor and an N-th-root metric. The auxiliary growth and local-integrability proofs are in the notes.

See [lecture-23/notes.md](lecture-23/notes.md), [lecture-24/notes.md](lecture-24/notes.md), and [sources.md](sources.md). Each notes file starts with the essential preparation, followed by optional details. No “Earlier inputs” footers have been restored. Numbered references to our seminar retain the known speaker's name.

Talk preparation checklist: [HOW TO GIVE A TALK](https://github.com/danimalabares/archive/blob/main/archive/HOW_TO_GIVE_A_TALK.txt), saved verbatim from Daniel.
