# Lecture 23 — teaching notes

41 frames, including title and reading slide. The working aim is roughly one substantial idea per frame, as in the dbar-Poincaré decks; the frame count is not a claim about a fixed lecture duration.

## Route

- 2–3: motivate the theorem with the evaluation exact sequence.
- 4–10: go slowly from the fibre norm to the multiplier ideal. Compute the radial exponent on the board. At equality the logarithmic divergence is essential.
- 11–16: curvature and the smooth estimate. Bochner–Kodaira/Kodaira vanishing are recalled from lecture 16 (Vanya), not treated as new course material.
- 17–25: replace the smooth Dolbeault resolution with the weighted complex. This is the conceptual centre of the lecture.
- 26–32: explain how an estimate solves an equation, and state exactly which singular-weight extension is used.
- 33–36: finish Nadel and return to the original evaluation map.
- 37–41: historical context, next lecture, and checkpoints.

## Conventions and details to say aloud

We use squared frame norm h(e,e)=exp(-2φ), hence iΘ_h=2i∂∂bar φ. A positive curvature current has locally psh weights after the appropriate smooth potential is subtracted. The local integrability definition alone works more generally, but Nadel needs this curvature hypothesis.

The ideal I_h is a subsheaf of O_X. The integrable holomorphic sections are B⊗I_h; integrable holomorphic top forms with values in B are K_X⊗B⊗I_h. Keep these three objects distinct.

For a nonzero holomorphic germ of order k, angular integration of its Taylor expansion has leading order r^(2k), with a positive leading angular integral. This justifies the radial criterion k+n>a even when the leading polynomial vanishes in some directions. The zero germ is always integrable.

For the degree-zero kernel, the weight is locally bounded above, so weighted L2 implies unweighted local L2. Distributional holomorphicity then gives genuine holomorphicity. The coefficient times dz_1∧…∧dz_n is locally integrable precisely when its coefficient belongs to I_h.

The sheaf domain is u and ∂bar u locally L2. Do not impose an adjoint condition: that is a global Hilbert-space issue, not the fine sheaf we use. The derivative condition is automatic for a closed representative and for a primitive with ∂bar u=f.

## What is proved and what is imported

The slides prove the radial ideal calculation, frame independence, fineness, the sheaf-cohomology deduction, and the Hilbert-space estimate-to-solution argument. Smooth Bochner–Kodaira and smooth Hodge theory are previous inputs.

Two analytic results are explicitly imported:
1. weighted local ∂bar solvability for psh/quasi-psh weights;
2. the global singular-weight L2 existence theorem on compact Kähler manifolds with a strict current lower bound.

The approximation slide is an explanation of the mechanism, **not** a full proof of the second theorem. A general positive singular metric need not be globally smoothable while preserving strict positivity; pretending otherwise would already force false ampleness conclusions. Use the complete-metric/exhaustion and regularization theorem in the analytic reference.

For a fully self-contained analytic lecture, the next preparation task is to expand slides 21–23 and 31–32 with the precise exhaustion, density, operator-domain, and weak-limit argument. That expansion would require time beyond the present draft.

## Functional analysis details

Let T and S be closed densely defined operators with ST=0. Z=ker S is closed. Regard T as a closed operator T_0 into Z; its domain is dense in the source. Its adjoint is the restriction of T* to Z. The basic estimate on Dom(T*)∩Dom(S) gives ||v|| ≤ c^(-1/2)||T_0*v|| for v in Dom(T_0*).

Use the inner-product convention linear in the first variable. Define the linear functional ℓ(T_0*v)=〈v,f〉. The lower bound makes T_0* injective, hence ℓ well defined. Hahn–Banach extends it, Riesz represents it by u, and the equality 〈T_0*v,u〉=〈v,f〉 says u lies in Dom(T_0**) and T_0**u=f. Closedness gives T_0**=T_0. No smooth harmonic representative is used in the singular case.

For local approximation, first restrict to a relatively compact ball on which f has finite weighted norm. Fix a strictly positive quadratic correction. Smooth psh approximants decrease on smaller balls, so the norms increase. Uniform estimates give weakly convergent subsequences in each fixed approximating weighted space; diagonal extraction, lower semicontinuity, and monotone convergence produce the limiting weighted bound. Global patching is not accomplished by merely partitioning solutions.

## Previous material

- Kähler identities: lecture 10 (Beatrice), behind the Bochner–Kodaira identity.
- Chern connection: lecture 14 (Yan), behind the meaning of Θ.
- Bochner–Kodaira/Kodaira vanishing: lecture 16 (Vanya).
- Dolbeault, fine resolutions, partitions of unity, distributional ∂bar, psh functions, and currents: used by name. Do not invent unconfirmed seminar speaker assignments.
- Holomorphic convexity is part of the analytic background for Stein/exhaustion methods. It is not a separate algebraic step in the displayed proof of Nadel, and one should not claim that holomorphic convexity by itself supplies the L2 estimate.

The plan deck is intentionally preserved rather than silently rewritten to match this expanded teaching route.
