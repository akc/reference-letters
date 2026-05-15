# assessment report

This report is based on the local file `hi-von-thesis-en.pdf`, Atli Fannar's
homepage, and his CV page, both fetched on 2026-05-14. I have not done a full
proof audit. The assessment concerns substance, coherence, originality, and
professional profile.

## thesis in brief

The thesis, `Enumerating score sequences and permutations by inversions and
forbidden patterns`, is a paper-based Ph.D. dissertation in mathematics at the
University of Iceland, April 2026. The PDF has 124 pages including front matter;
the bibliographic note gives 110 pp. It contains four papers.

- Paper I settles Hanna's conjecture on tournament score sequences, gives a
  factorization theorem, and derives a closed formula and quadratic-time
  algorithm.
- Paper II enumerates permutations with few inversions through generating
  functions for the main diagonal and subdiagonals of the Mahonian triangle.
- Paper III enumerates pattern-avoiding indecomposable permutations by
  inversions for all combinations of classical patterns of length at most 3.
- Paper IV encodes pattern-avoiding permutations as walks in directed graphs
  and applies this to the 1324 Stanley-Wilf limit problem.

## assessment of the thesis

The thesis is good to strong for a recent Ph.D. It has a coherent theme:
enumerative combinatorics, especially permutations studied through inversions,
decompositions, bijections, generating functions, and forbidden patterns.

The strongest anchor is Paper I. It takes a century-old counting problem for
tournament score sequences and turns Hanna's recursion into a corollary of a
clean factorization theorem. The resulting closed formula and quadratic-time
recursion are concrete mathematical payoffs, not just reformulations.

Paper II is also solid. The factorization reducing all subdiagonals to `S_0(x)`
is elegant, and the later description of `S_0(x)` through `R(xC(x))`, partitions,
compositions, and Lambert series gives the result several useful faces.

Paper III is systematic rather than spectacular. Its value is coverage: it treats
all combinations of patterns of length at most 3, often by explicit bijections to
known objects such as partitions, fountains, parallelogram polyominoes, and
Gorenstein partitions. This is useful taxonomic work in a small but real niche.

Paper IV is the most interesting unfinished part. The graph-walk encoding and
Perron-Frobenius machinery are natural and promising. For 1324, however, the
headline lower bound of 10.418 is conditional on Conjecture 8. If that conjecture
were proved, this would improve the known lower bound 10.271, but the thesis
does not give an unconditional new bound. The author's own discussion suggests
that this partition may converge well below the numerical expectation near 11.6.

The exposition is generally clear. The introduction is readable and pedagogical,
though sometimes more elementary than a specialist needs. A few typos and rough
edges remain, especially in Paper IV. The paper-based structure also means the
unifying narrative is weaker than in a monograph thesis. These are presentational
limits, not major mathematical defects.

I see no obvious structural red flags in the statements and proof strategies I
checked. Three of the four thesis papers have appeared in peer-reviewed venues.
The main caveat is that Paper IV should be treated as exploratory until its key
conjecture is proved or replaced by an unconditional argument.

Overall, this is a credible and technically competent Ph.D. thesis in enumerative
combinatorics. Its best parts combine bijective structure with usable formulas or
algorithms. Its weakest part is not weak mathematics, but an ambitious method
whose main 1324 consequence remains conditional.

## assessment of Atli Fannar

Atli Fannar's public profile is that of an early-career combinatorialist with a
strong programming and contest background. His CV lists a double BSc in
mathematics and computer science from the University of Iceland, an MSc in pure
mathematics from the University of Zurich, and a Ph.D. in combinatorics from
the University of Iceland.

The publication record is credible for this career stage. By May 2026 his CV
lists five publications or preprints: three thesis papers in PAMS, EJC, and
DMTCS; the submitted 1324-walks preprint; and the non-thesis Taxman paper in
Discrete Applied Mathematics. Two thesis papers are single-authored, including
the DMTCS classification paper and the 1324-walks preprint. That is meaningful
evidence of independence.

The teaching and competition record is unusually substantial. The CV lists
teaching at the University of Reykjavik and the University of Iceland, including
competitive programming, mathematical programming, C++, linear algebra, graph
theory, formal languages, and other courses. It also lists long-running work as a
problem author, organiser, jury member, IMO deputy, and IMO team leader.

His research style seems problem-driven and constructive. He uses bijections,
generating functions, inversion-table encodings, computational experiments, and
algorithmic checks. The contest background appears to reinforce this style. The
CV does not yet show a broad independent program outside enumerative
combinatorics and adjacent algorithmic topics, but that is normal at Ph.D.
completion.

For a research position, his strongest case is in enumerative combinatorics,
permutation patterns, symbolic or computational experimentation, and teaching
programming-heavy mathematics. I would want letters and a future plan that show
how he intends to turn exploratory work like Paper IV into proved theorems or
general machinery.

## sources

- Local file: `hi-von-thesis-en.pdf`.
- Atli Fannar homepage: <https://atliff.is/>.
- Atli Fannar CV: <https://atliff.is/cv/>.
- Thesis handle linked from the homepage:
  <https://hdl.handle.net/20.500.11815/8049>.
- 1324-walks preprint: <https://arxiv.org/abs/2512.19462>.
