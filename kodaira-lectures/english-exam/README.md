# English exam: how sections give an embedding

A ten-slide adaptation of the opening of lecture 23, designed for a talk of about nine minutes, leaving a buffer under the ten-minute limit. The subject is the geometric mechanism behind Kodaira embedding, not its full analytic proof. The spoken explanation assumes general mathematical knowledge, but no Hodge theory.

- Source: `lecture-english-exam.tex`
- Presentation: `lecture-english-exam.pdf` (generated locally, following the repository's PDF ignore rule)
- Rehearsal: `speaker-notes.md`

Build from this directory:

```sh
pdflatex -interaction=nonstopmode -halt-on-error lecture-english-exam.tex
pdflatex -interaction=nonstopmode -halt-on-error lecture-english-exam.tex
```

The deck uses `../preamble.tex` and the existing Kodaira photo in `../assets/`. Keep it within the Kodaira directory when compiling. The main lecture decks are unchanged.

## Scope and sources

The theorem and section-separation argument are adapted from `../lecture-23/lecture-23.tex` and its preparation notes. The cohomology slide presents the lifting mechanism conditionally; the required vanishing is a substantial analytic input, not a consequence of the elementary examples. Positivity refers to a metric on the line bundle, not sectional curvature of X. The talk omits the course recap, curvature computations, and Nadel's theorem to stay within the time limit.

For mathematical sources and image provenance, see `../sources.md`. The Kodaira photo is credited to Konrad Jacobs / MFO, CC BY-SA 2.0 Germany, https://commons.wikimedia.org/wiki/File:Kodaira_Kunihiko.jpg . His Fields Medal year follows https://www.ias.edu/scholars/kunihiko-kodaira . The cusp drawing is reused from lecture 23 and depicts a real slice.
