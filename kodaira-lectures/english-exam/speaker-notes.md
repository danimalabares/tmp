# Speaking notes

Target: **9 minutes**, with one minute of buffer. These are suggested words, not a script to memorize. Practise once with a timer, including pauses and pointing at the formulas. The examiner may ask questions about the chosen topic.

| Slide | Time | Cumulative |
| --- | ---: | ---: |
| 1. Title | 0:25 | 0:25 |
| 2. Projective coordinates | 1:05 | 1:30 |
| 3. Sections | 1:15 | 2:45 |
| 4. Kodaira theorem | 0:55 | 3:40 |
| 5. Kodaira picture | 0:25 | 4:05 |
| 6. Three conditions | 1:00 | 5:05 |
| 7. Point separation | 0:55 | 6:00 |
| 8. Tangent directions | 1:05 | 7:05 |
| 9. Vanishing | 1:20 | 8:25 |
| 10. Conclusion | 0:35 | 9:00 |

## 1. Title

“Today I would like to explain one geometric idea behind Kodaira's embedding theorem. The question is: how can we describe a complex manifold using global coordinates? I will explain how sections provide these coordinates, and what conditions make the resulting map an embedding.”

## 2. Coordinates up to a common scale

“First, let me recall projective coordinates. We take a tuple of complex numbers, not all zero, and identify two tuples if one is a nonzero multiple of the other. For example, one colon two represents the same point as two colon four. Wherever the first coordinate is nonzero, we divide by it and recover ordinary coordinates. The advantage is that no single coordinate has to stay nonzero everywhere. Different charts can use different denominators. We want to construct a map from our manifold into this space.”

## 3. Sections supply the coordinates

“A line bundle attaches a one-dimensional complex vector space to every point of the manifold. Locally, it looks like a product with the complex numbers. A holomorphic section is a holomorphic choice of one vector in each fibre. After choosing a local frame, we can express sections as ordinary functions. These functions give the entries in our projective coordinates. If we change the frame, all the entries change by the same nonzero factor. Projective space ignores that common factor. So the construction does not depend on the frame. We still need to make sure that the entries are not all zero.”

## 4. Kodaira embedding theorem

“Kodaira's theorem says that a positive holomorphic line bundle on a compact complex manifold gives an embedding into projective space, after taking a sufficiently large tensor power. Positive refers to the curvature of a metric on the line bundle. I will not explain that analytic condition in detail today. The important conclusion is that sections of a high tensor power provide enough coordinates to realize our manifold as a complex submanifold of projective space. Let us see what ‘enough’ means.”

## 5. Kodaira

“This is Kunihiko Kodaira, who received the Fields Medal in nineteen fifty-four. His work connects complex geometry with analysis. In this theorem, an analytic positivity condition ultimately produces a geometric map.”

## 6. Three conditions

“There are three things to check. First, the sections must have no common zero. This is called base-point freeness, and it makes the map defined everywhere. Second, the sections must distinguish different points, so the map is injective. Third, they must detect tangent directions, so the derivative is injective as well. That is the immersion condition. Since our manifold is compact and projective space is Hausdorff, an injective immersion is an embedding. Let us look at the last two conditions more closely.”

## 7. Separating two points

“Take two different points, x and y. Suppose we can find a section which has value one at x and zero at y, and another section with the opposite values. Here one means a chosen nonzero vector in the corresponding fibre. The two tuples cannot be scalar multiples of each other: their first two entries already distinguish them. Therefore the projective images are different. This is why the ability to prescribe section values gives injectivity.”

## 8. Tangent directions

“Injectivity alone is not enough. Consider the map taking t to t squared, t cubed. It is injective, but both derivatives vanish at zero. Its image has a cusp, shown here in the real picture. For an immersion, no nonzero tangent vector may disappear under the derivative. In our projective map, we use local ratios of sections as coordinates. We want their derivatives to detect every tangent vector. One sufficient way to do that is to prescribe all first derivatives of suitable sections.”

## 9. Where vanishing enters

“So the problem has become a question about interpolation: can we find global sections with chosen values and first derivatives? Cohomology provides a way to answer this. H zero is the vector space of global sections. The first arrow records their local data. The next arrow sends those data to a possible obstruction to extending them globally. Exactness says that data can be lifted precisely when this obstruction is zero. If the whole H one group vanishes, every choice of data lifts. The ideal I specifies which data we are prescribing. The difficult analytic part of Kodaira's theorem supplies the required vanishing for high tensor powers. Today I am explaining how that vanishing produces the embedding.”

## 10. Conclusion

“To conclude, the mechanism is this. Vanishing allows us to prescribe local data using global sections. These sections distinguish points and tangent directions. They therefore define an injective immersion, and compactness makes it an embedding. This is the geometric reason that producing enough sections produces global coordinates. Thank you.”

## Short answers for questions

**Why projective space rather than affine space?** On a connected compact complex manifold, every global holomorphic function is constant. Sections can be nonconstant because they take values in a line bundle. Their ratios give projective coordinates.

**Why is the cusp map injective?** If two parameters have equal squares, they differ by a sign. Equal cubes then force them to be equal, including at zero. Its derivative is (2t,3t²), which vanishes at zero.

**Why does compactness help?** A continuous injection from a compact space into a Hausdorff space is a homeomorphism onto its image. The immersion condition supplies the local smooth, here holomorphic, submanifold structure.

**What is a tensor power?** The fibre of L to the N is the N-fold tensor product of the fibre of L. Locally its transition functions are the Nth powers of those of L.

**What precisely is the middle space on slide 9?** It is H0(X,A tensor (O_X/I)). For two points, I=m_x intersect m_y and this space is the direct sum of the two one-dimensional fibres. For first jets, use I=m_x².

**Why do prescribed derivatives suffice?** In coordinates centred at x and a local frame, choose s0=1+terms of order at least two, and sj=zj+terms of order at least two. Then d(sj/s0) at x equals dzj. These differentials detect all tangent directions.

**Is this a full proof of Kodaira embedding?** No. It explains the geometric deduction once the necessary vanishing is available. The existence of suitable metrics and uniform vanishing for sufficiently large powers is the main remaining work.

**What does positive mean?** A smooth Hermitian metric has a Chern curvature form Theta. The real (1,1)-form iTheta is positive if iTheta(v,Iv)>0 for every nonzero real tangent vector v. It is positivity of a bundle metric, not positive sectional curvature of the manifold.

**Can you give a concrete embedding?** The map [u:v] to [u²:uv:v²] embeds the projective line as a conic in the projective plane. The three degree-two monomials are sections of O(2).

## Useful spoken forms

- H0: “H zero”; H1: “H one”.
- L tensor N: “the Nth tensor power of L”.
- Phi: “phi”, pronounced like “fie”.
- “The sections have no common zero.”
- “The map is injective, and its differential is injective.”
- “Every choice of local data extends to a global section.”
- “Let me explain that in a simpler example.”
- “I am using this theorem as an input here.”
