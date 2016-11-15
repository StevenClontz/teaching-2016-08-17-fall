---
layout: page
title: "Part 6: Power Series"
---

---

\\(
  \newcommand{\\<}{\langle}
  \newcommand{\\>}{\rangle}
\\) <!-- TODO make angle brackets parentheses -->

## 6.1 Power Series

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 9.7

### 6.1.1 Definition

<iframe width="560" height="315" src="https://www.youtube.com/embed/vR43raJbw84" frameborder="0" allowfullscreen></iframe>

- A power series is a function defined by
  \\(f(x)=\sum_{n=0}^\infty c_nx^n=c_0+c_1x+c_2x^2+c_3x^3+\dots\\)
  for a coefficient sequence \\(\\<c_n\\>\_{n=0}^\infty\\).
- **Example**
  Expand the first four terms of the power series
  \\(\sum_{m=0}^\infty (2m+1)x^m\\).
- **Example**
  Expand the first four terms of the power series
  \\(\sum_{k=2}^\infty \frac{x^{2k}}{k!}\\).
- The geometric series formula \\(\sum_{n=0}^\infty ar^n\\)
  allows us to simplify certain series where \\(|r|<1\\).
- **Example**
  Simplify
  \\(f(x)=\sum_{n=0}^\infty x^n=1+x+x^2+x^3+\dots\\) with domain \\(|x|<1\\).
- **Example**
  Simplify
  \\(p(x)=\sum_{j=1}^\infty (\frac{x}{3})^{2j}=
  \frac{x^2}{9}+\frac{x^4}{81}+\frac{x^6}{729}+\dots\\)
  with domain \\(|x|<3\\).

### 6.1.2 Domains of Power Series

<iframe width="560" height="315" src="https://www.youtube.com/embed/TZIUoGfVME4" frameborder="0" allowfullscreen></iframe>

- The domain of a power series may be determined by applying the Root or
  Ratio Test to determine for which \\(x\\) values the series converges.
  On the endpoints where these tests are inconclusive, other
  techniques must be used.
- **Example**
  Find the domain of
  \\(f(x)=\sum_{n=1}^\infty\frac{x^n}{n}=x+\frac{x^2}{2}+\frac{x^3}{3}+\dots\\).
- **Example**
  Find the domain of
  \\(h(x)=\sum_{n=0}^\infty\frac{(3-2x)^n}{n!}=
  1+(3-2x)+\frac{(3-2x)^2}{2}+\frac{(3-2x)^3}{6}+\dots\\).
- **Example**
  Find the domain of
  \\(g(x)=\sum_{k=2}^\infty\frac{(3x)^n}{n\ln n}=
  \frac{9x^2}{2\ln2}+\frac{27x^3}{3\ln3}+\frac{81x^4}{4\ln4}+\dots\\).


---

## 6.2 Taylor and Maclaurin Series

- University Calculus: Early Transcendentals (3rd Ed)
    - 9.8

### 6.2.1 Power Series from Functions

### 6.2.2 Taylor Polynomials

### 6.2.3 Maclaurin Series for \\(e^x\\), \\(\\sin x\\), \\(\\cos x\\)


---

## 6.3 Convergence of Taylor Series

- University Calculus: Early Transcendentals (3rd Ed)
    - 9.9

### 6.3.1 Taylor's Formula

### 6.3.2 Remainder Estimation Theorem

### 6.3.3 Convergence of Maclaurin Series for \\(e^x\\), \\(\\sin x\\), \\(\\cos x\\)


---

## 6.4 Manipulating Power Series

- University Calculus: Early Transcendentals (3rd Ed)
    - 9.7, 9.9

### 6.4.1 Arithmetic and Compositions of Power Series

### 6.4.2 Differentiation and Integration of Power Series

### 6.4.3 Common Power Series
