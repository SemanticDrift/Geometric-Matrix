# The Geometric Matrix
**Rational Derivation of the Pythagorean Triangle**
*Series: Mathematical Foundations for Universal Systems*

**Author:** Carolina Johnson (CJ)  
**Date:** April 2026  
**DOI:** [10.5281/zenodo.19490969](https://doi.org/10.5281/zenodo.19490969)  
**ORCID:** [0009-0002-8819-3347](https://orcid.org/0009-0002-8819-3347)

---

## Overview

The Pythagorean theorem is correct but incomplete. It describes the relationship between the three sides of a right triangle, but it does not explain where the triangle sits on a circle, how it balances around its center, or why a rope of fixed length pinned at three points must form a specific triangle.

The Geometric Matrix fills that gap. It introduces four variables — the left anchor `a`, centroid `b`, span `c`, and right boundary `d` — that satisfy a closed symmetry matrix. From any two variables, the remaining two are forced by arithmetic. The system generates triangles, their circumcircles, and their bounding squares from a single boundary span, with no trigonometry required and no floating-point drift introduced at the source.

Ancient builders used a 12-knot rope to produce a 3-4-5 right triangle. The standard theorem confirms it works. The Geometric Matrix explains why it must work.

---

## Key Contributions

- **Unified Framework:** Replaces three separate mathematical frameworks (trigonometry, Heron's formula, and the Pythagorean theorem) with a single coordinate matrix.

- **Delta Classification:** The invariant `Δ = b² + c² - d²` classifies all triangles as acute, right, or obtuse without trigonometry.

- **3-4-5 Family:** The right-triangle equilibrium condition `Δ = 0` forces `d = 5a`, generating the 3-4-5 family as an arithmetic necessity of the boundary `[1, 5]`.

- **Rational Circumcenter:** The circumcenter is derived through rational partitioning with only one square root at the end — no trigonometric functions, no Heron's formula.

- **Full Cycle:** From the same matrix, the triangle, its circumcircle, and its bounding square are derived as states of one system.

---

## The Matrix

For any anchor boundary `[a, d]` with `a < d`:

a = b - c/2
b = (a + d) / 2
c = d - a
d = b + c/2


These are not hypotheses. They are the definitions of midpoint and distance. Given `a` and `d`, the values `b` and `c` are forced. Any one variable can be derived from any two others. The system is closed by arithmetic.

---

## The Logic Engine

An interactive tool is included in this repository. Enter any two of the four variables and the engine derives the remaining two, computes Δ, classifies the triangle, and renders the geometry in real time.

The engine runs in any browser. No dependencies.

### Live Interactive Engine

👉 [https://semanticdrift.github.io/Geometric-Matrix/](https://semanticdrift.github.io/Geometric-Matrix/)

---

## Repository Contents

| File | Description |
|------|-------------|
| `README.md` | This file |
| `Geometric Matrix.pdf` | Full paper |
| `geometric_matrix_engine.html` | Interactive Logic Engine |

---

## Dependencies

| Framework | DOI |
|-----------|-----|
| The Origami Principle | [10.5281/zenodo.18293883](https://doi.org/10.5281/zenodo.18293883) |

Full publication list: [https://www.SemanticDrift.net](https://www.semanticdrift.net)

---

## Citation

```
Johnson, C. (2026). The Geometric Matrix: Completing the Pythagorean Theorem.
Series: Mathematical Foundations for Universal Systems.
SemanticDrift. DOI: https://doi.org/10.5281/zenodo.19490969
```

---

## License

© 2026 Carolina Johnson (CJ)
Licensed under Creative Commons Attribution 4.0 International (CC BY 4.0)
Attribution required. [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)
