# Sources and visual provenance

## Teaching style and course sources

- Existing repository decks: [dbar-poincare/lecture-12.tex](../dbar-poincare/lecture-12.tex) (36 frames) and [lecture-13.tex](../dbar-poincare/lecture-13.tex) (51 frames). Their typography, sparse frame rhythm, explicit intermediate calculations, and portrait pauses guided the drafts.
- Misha Verbitsky, [Kähler geometry, IMPA 2025](http://verbit.ru/IMPA/Kahler-2025/). The supplied PDF archive was used: `30-slides-Kahler-2025-23.pdf` and `31-slides-Kahler-2025-24.pdf`. Lecture 23 supplies the weighted-resolution/Nadel route; lecture 24 supplies embedding and the nef-and-big metric construction.
- [Heap Project](https://github.com/danimalabares/heap-project): the smooth Bochner–Kodaira/Kodaira proof developed in the preceding discussion is retained as a short recap. The archived plan remains byte-for-byte unchanged.

## Analytic reference

Jean-Pierre Demailly, [L2 vanishing theorems for positive line bundles and adjunction theory](https://arxiv.org/abs/alg-geom/9410022), CIME lecture notes (1994). This is the reference for the singular-weight L2 theorem and weighted local resolution. The draft explains the proof mechanism while explicitly treating the full singular-weight existence result as an analytic input.

## Historical facts

- Alan Michael Nadel, [Multiplier ideal sheaves and Kähler–Einstein metrics of positive scalar curvature](https://annals.math.princeton.edu/1990/132-3/p04), Annals of Mathematics 132 (1990), 549–596, DOI 10.2307/1971429. The abstract explains the Kähler–Einstein origin and how multiplier ideals record failure of an estimate. This supports lecture 23's historical pause.
- [IAS scholar profile: Kunihiko Kodaira](https://www.ias.edu/scholars/kunihiko-kodaira). Supports the 1954 Fields Medal, first Japanese recipient, and connection with harmonic analysis/vanishing. The slide paraphrases rather than quotes the profile.
- Yujiro Kawamata, [A Generalization of Kodaira–Ramanujam's Vanishing Theorem](https://geodesic.mathdoc.fr/item/MAN_1982__261_182862/), Math. Ann. 261 (1982), 43–46.
- Eckart Viehweg, “Vanishing theorems,” J. reine angew. Math. 335 (1982), 1–8: [author's publication list](https://esaga.uni-due.de/eckart.viehweg/ecpubl/), item 7. Together these support the chronology frame. We do not imply Nadel's theorem was the original proof of Kawamata–Viehweg.

## Pictures

- `assets/Pierre_Dolbeault.jpg` is an unchanged copy of the existing `dbar-poincare/Pierre_Dolbeault.jpg` repository asset (blob `8ac82ca940a80d3d52acd6cdd3ce0e00fff58560`). No new photographer or license attribution has been invented; consult the original asset's provenance before external republication.
- Integrability threshold: original editable TikZ diagram of k+n>a; open endpoints indicate divergence at equality.
- Application map: original editable TikZ diagram.
- Cutoff annulus: original editable TikZ diagram indicating where bounded curvature loss occurs.
- Cusp: original editable TikZ plot of the real slice (t²,t³); it illustrates, but does not characterize, failure of immersion.
- Blowup: original editable schematic of contraction of E; not a literal drawing of a complex surface.
- Section growth: original editable schematic comparing polynomial orders; its caption makes clear that the big lower bound need hold only along a subsequence.

## Verification

Both new decks compiled successfully with pdfLaTeX, with no overfull boxes. All pages were rendered and reviewed in contact sheets; individual picture/formula pages were checked at higher resolution. The original plan was moved without mathematical edits.
