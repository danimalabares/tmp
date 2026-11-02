# Lecture 24 — the metrics and Kawamata–Viehweg

21 slides. Continue the argument from lecture 23 (Daniel), rather than introducing the section-separation mechanism again.

## Essential preparation

Prepare the cutoff construction and its uniform curvature bound, the sum of two point weights, and the fixed-divisor N-th-root construction. The values-and-jets argument has already been presented in lecture 23 (Daniel).

The auxiliary projective growth bound and the small-exponent integrability lemma may be stated. Their supporting arguments remain in the optional notes.

## Route

- 2–3: recall the precise unfinished task and announce the remaining steps.
- 4–6: construct the singular metrics, including one N valid for all points and pairs.
- 7–8: conclude embedding and pause for Kodaira's historical context.
- 9–13: define nef and big, illustrate the distinction from ample, and state Kawamata–Viehweg.
- 14–19: fixed divisor, positive metric, mild root singularities, and Nadel.
- 20–21: chronology and comparison of the two applications.

At slide 6, stress that two cutoffs may overlap: curvature lower bounds add, while the other point's weight is smooth as a germ at each singularity. There is no compactness assertion about X×X minus the diagonal.

At slide 14, explain the kernel of the restriction map:
h0(X,L^m(-A)) ≥ h0(X,L^m) - h0(A,L^m|_A).
A nonzero section gives L^d=O(A+D). Keep D fixed while N grows.

## Optional details

The following expands the short arguments and records the precise hypotheses. It is not an additional slideshow.

## Embedding details

Fix a Kähler form and positive metric on L; a positive curvature form on the initial compact complex manifold already provides such a Kähler form. A smooth metric on K_X^(-1) has curvature bounded below by -C_0ω. Use B_N=L^N⊗K_X^(-1) for Nadel: applying Nadel directly to L^N would leave an unwanted K_X factor.

Choose a finite atlas V_i compactly contained in U_i, with the V_i covering X. There is a radius ρ_i>0 such that Euclidean balls of radius 2ρ_i about all centres in V_i lie in U_i. Translate a fixed radial cutoff at that radius. On its transition annulus, derivatives of χ and log|z-z(x)| are uniformly bounded. The coordinate metrics are uniformly comparable with ω on the compact chart closures. This supplies a bound independent of x.

For pairs x≠y, sum two weights with coefficient n. Their supports **need not be disjoint**. The weight centred at y is smooth in some neighbourhood of x, however close the points are; hence it does not change the germ ideal at x. The curvature lower bound is at worst the sum of two uniform bounds. For jets use coefficient n+1. One N therefore works simultaneously for every x, every pair, and every first jet. Compactness of X×X minus the diagonal is neither true nor needed.

The value/jet separation proof is in lecture 23's notes. Recall only its conclusion here: once the uniform metrics give H1-vanishing, the complete linear system is an injective immersion, and compactness makes it a holomorphic embedding. Projectivity in the algebraic sense follows from Chow's theorem, if that identification is not taken as the definition.

The positivity/ample equivalence is used only after proving embedding, so using an ample M_N to choose a positive metric later is not circular.

## Kawamata–Viehweg details

We prove the integral line-bundle version on a smooth projective complex variety. This is not the full Q-divisor/log-pair formulation.

Nef means nonnegative degree on every curve, equivalently membership in the closure of the ample cone in this projective setting. Use the established projective result nef+ample=ample. Do not replace nef by existence of a smooth semipositive metric, and do not claim that strict positivity on all curves alone implies ampleness in general.

Choose A smooth and very ample (Bertini). The growth bound on A uses Serre vanishing and the Hilbert polynomial; these are additional explicit projective inputs in the draft, not implicitly attributed to an unverified earlier lecturer. The dimension argument only needs a subsequence of m along which h^0(L^m)≥c m^n. Its kernel supplies a nonzero section of L^d(-A), with zero divisor D. For curves, A is a finite reduced set and the same bound is O(1). The dimension-zero case is immediate.

**Keep D fixed.** For N>d, M_N=L^(N-d)⊗O(A) is ample, and L^N=M_N⊗O(D). The metric (h_N h_D)^(1/N) has strict curvature lower bound ε_Nω. ε_N may tend to zero; the theorem needs just one chosen positive value.

With h(e,e)=exp(-2φ), Poincaré–Lelong is i∂∂bar log|f|²=2π[div(f)]. Therefore the divisor metric |f_D|^(-2) has curvature 2π[D]. These factors of 2 and π are consistent throughout both drafts.

For the general integrability lemma, choose a coordinate w for which f is Weierstrass regular after a linear coordinate change. Preparation expresses f as a unit times a monic polynomial of degree k. On a smaller polydisc the unit and its reciprocal are bounded, and all roots are uniformly bounded. For each fixed z', factor the polynomial in w; the roots need not be holomorphic functions of z'. Hölder bounds the w-integral when ck<1 by uniform translated-disc integrals. Fubini completes the local proof. A finite cover of the compact divisor gives one exponent. If D is empty the ideal is automatically trivial.

## What we use from the course

Nadel: lecture 23 (Daniel). Chern curvature, psh weights, currents, and Poincaré–Lelong enter the metric constructions. Dolbeault/cohomology enters through Nadel and the long exact sequence. Holomorphic convexity is not an additional step in either application once Nadel is available.

Known speaker attributions are retained when seminar lecture numbers are mentioned; no assignments for other lectures have been guessed.
