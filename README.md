# The Geometric Matrix

**Rational Derivation of the Pythagorean Triangle**
*Series: Mathematical Foundations for Universal Systems*

**Author:** Carolina Johnson (CJ)
**Date:** April 2026
**DOI:** [10.5281/zenodo.19490969](https://doi.org/10.5281/zenodo.19490969)
**ORCID:** [0009-0002-8819-3347](https://orcid.org/0009-0002-8819-3347)

---

## Overview

The Pythagorean theorem is correct, but it describes the relationship between the three sides of a right triangle. The Geometric Matrix adds the constructional context by introducing four variables, the left anchor `a`, centroid `b`, span `c`, and right boundary `d`, that satisfy a closed symmetry matrix.

Given any two variables, the remaining two are determined arithmetically. From an anchor boundary, the Matrix generates the corresponding triangle, circumcircle, and bounding square as related geometric states of the same system, without requiring trigonometric functions.

The familiar 3-4-5 triangle appears as the equilibrium case of the system. The standard Pythagorean theorem confirms the right angle; the Geometric Matrix provides the arithmetic construction and boundary relationships that produce it.

---

## Key Contributions

* **Unified Constructional Framework:** Provides a single coordinate-based matrix for constructing and relating the triangle, its circumcircle, and its bounding square.
* **Delta Classification:** The invariant `Δ = b² + c² - d²` classifies the resulting triangle as acute, right, or obtuse without trigonometry.
* **3-4-5 Family:** The right-triangle equilibrium condition `Δ = 0` forces `d = 5a`, generating the 3-4-5 family as an arithmetic consequence of the boundary `[1, 5]`.
* **Rational Circumcenter Construction:** The circumcenter is derived through rational partitioning. The resulting quantities are obtained from `b`, `c`, and `d` through rational operations and one square root, without trigonometric functions or Heron's formula.
* **Full Geometric Cycle:** The triangle, its circumcircle, and its bounding square are derived as related states of the same matrix.

---

## The Matrix

For any anchor boundary `[a, d]` with `a < d`:

```
a = b - c/2
b = (a + d)/2
c = d - a
d = b + c/2
```

These relations express midpoint and distance relationships. Given `a` and `d`, the values of `b` and `c` are determined directly. Conversely, the variables can be recovered from other valid pairs.

The system is therefore closed under arithmetic relations among the four variables.

---

## Delta Classification

The Matrix defines the invariant:

```
Δ = b² + c² - d²
```

Its sign provides the geometric classification:

| Condition | Classification |
| --------- | -------------- |
| `Δ > 0`   | Acute          |
| `Δ = 0`   | Right          |
| `Δ < 0`   | Obtuse         |

The equilibrium condition `Δ = 0` produces the right-triangle family. Under the normalized boundary `a = 1`, this gives:

```
[a, d] = [1, 5]
```

with:

```
b = 3
c = 4
d = 5
```

Thus the 3-4-5 triangle emerges directly from the Matrix relations.

---

## The Logic Engine

An interactive tool is included in this repository. Enter any two of the four variables and the engine derives the remaining two, computes `Δ`, classifies the resulting triangle, and renders the geometry in real time.

The engine runs directly in a web browser with no external dependencies.

### Live Interactive Engine

👉 https://semanticdrift.github.io/Geometric-Matrix/

---

## Repository Contents

| File                           | Description              |
| ------------------------------ | ------------------------ |
| `README.md`                    | This file                |
| `Geometric Matrix.pdf`         | Full paper               |
| `geometric_matrix_engine.html` | Interactive Logic Engine |

---

## Dependencies

| Framework             | DOI                                                                |
| --------------------- | ------------------------------------------------------------------ |
| The Origami Principle | [10.5281/zenodo.18293883](https://doi.org/10.5281/zenodo.18293883) |

Full publication list: https://www.SemanticDrift.net

---

## Citation

```
Johnson, C. (2026). The Geometric Matrix: Rational Derivation of the
Pythagorean Triangle. Series: Mathematical Foundations for Universal
Systems. SemanticDrift. DOI: https://doi.org/10.5281/zenodo.19490969
```

---

## License

© 2026 Carolina Johnson (CJ)

Licensed under Creative Commons Attribution 4.0 International (CC BY 4.0). Attribution required.

https://creativecommons.org/licenses/by/4.0/
