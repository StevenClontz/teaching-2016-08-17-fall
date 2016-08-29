---
layout: page
title: "Part 2: Advanced Integration Techniques"
---

\\(\newcommand{\sech}{\,\mathrm{sech}\,}\\)
\\(\newcommand{\csch}{\,\mathrm{csch}\,}\\)

---

## 2.1 Integration by Substitution

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 5.5, 5.6

### 2.1.1 Substitution and the Chain Rule

<iframe width="560" height="315" src="https://www.youtube.com/embed/QRUa732E61Q" frameborder="0" allowfullscreen></iframe>

- Reversing the Chain Rule \\(\frac{d}{dx}[f(g(x))]=f'(g(x))g'(x)\\)
  yields the Substitution Rule \\(\int f'(g(x))g'(x)\,dx=f(g(x))+C\\).
- This is often abbreviated as \\(\int f'(u)\,du=f(u)+C\\)
  by using the substitutions \\(u=g(x)\\) and \\(du=g'(x)dx\\).
- **Example**
  Find \\(\int 4(3+4x)^2\,dx\\).

<iframe width="560" height="315" src="https://www.youtube.com/embed/fC7suwFgwko" frameborder="0" allowfullscreen></iframe>

- **Example**
  Find \\(\int 3u^2\sin(u^3)\,du\\).
- **Example**
  Find \\(\int \frac{x}{x^2+1}\,dx\\).
- **Example**
  Find \\(\int \frac{4\sinh(\ln t)}{t}\,dt\\).


### 2.1.2 Substitution in Definite Integrals

<iframe width="560" height="315" src="https://www.youtube.com/embed/-fcaWT_qLcU" frameborder="0" allowfullscreen></iframe>

- When dealing with definite integrals, you may either convert the
  boundaries to \\(u\\)-values, or you must substitute back for the original
  variable before plugging in boundaries.
- **Example**
  Compute \\(\int_{1/4}^{1/2} 4(3+4x)^2\,dx\\).
- **Example**
  Compute \\(\int_0^1 z\sqrt{1-z}\,dz\\).
- **Example**
  Compute \\(\int_0^{\pi/4}\tan^2\theta\sec^2\theta\,d\theta\\).

### 2.1.3 Antiderivatives of Trigonometric Functions

<iframe width="560" height="315" src="https://www.youtube.com/embed/bHkxJk6bBAc" frameborder="0" allowfullscreen></iframe>

- The antiderivatives of the basic trig functions (besides sine/cosine)
  may be derived by using Substitution.
- **Example**
  Use Substitution to find \\(\int\tan\theta\,d\theta\\).
- **Example**
  Prove that \\(\int\csc x\,dx = -\ln|\csc x+\cot x|+C\\).

---

## 2.2 Integration by Parts

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 8.1

### 2.2.1 Parts and the Product Rule

<iframe width="560" height="315" src="https://www.youtube.com/embed/p2qwAALpV70" frameborder="0" allowfullscreen></iframe>

- We may reorder the Product Rule
  \\(\frac{d}{dx}[f(x)g(x)]=g(x)f'(x)+f(x)g'(x)\\)
  as follows:
  \\(f(x)g'(x)=\frac{d}{dx}[f(x)g(x)]-g(x)f'(x)\\).
- Integrating both sides
  yields the rule of Integration by Parts:
  \\(\int f(x)g'(x)\,dx=f(x)g(x)-\int g(x)f'(x)\,dx\\).
- This is often abbreviated as
  \\(\int u\,dv=uv-\int v\,du\\)
  by using the substitutions \\(u=f(x)\\) \\(du=f'(x)dx\\),
  \\(v=g(x)\\) \\(dv=g'(x)dx\\).
- **Example**
  Find \\(\int 2x\cos(x)\,dx\\).

<iframe width="560" height="315" src="https://www.youtube.com/embed/8wA0Onik9rc" frameborder="0" allowfullscreen></iframe>

- **Example**
  Find \\(\int te^t\,dt\\).
- Occasionally you'll need to use parts twice.
- **Example**
  Find \\(\int 3x^2\sinh(x)\,dx\\).
- Especially tricky problems may involve cycling back to the
  original integral.
- **Example**
  Find \\(\int e^w\sin(2w)\,dw\\).

### 2.2.2 Integrating Definite Integrals by Parts

- When using parts to evaluate definite integrals, do not forget
  to apply the bounds of integration to the entire integral.
- **Example**
  Find \\(\int_0^1 s^2e^s\,ds\\).

### 2.2.3 Antiderivatives of Logarithms

- Integrating logarithms is based on integration by parts.
- **Example**
  Use Integration by Parts to find \\(\int\ln x\,dx\\).
- **Example**
  Find \\(\int 4t\ln(t)\,dt\\).



---

## 2.3 Trigonometric Integrals

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 8.2

### 2.3.1 Trigonometric Identities

### 2.3.2 Integrating Products of Sine and Cosine

### 2.3.3 Integrating Products of Secant and Tangent



---

## 2.4 Trigonometric Substitution

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 8.3

### 2.4.1 Pythagorean Forms

### 2.4.2 Trigonometric Substitution



---

## 2.5 Integrating with Partial Fractions

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 8.4

### 2.5.1 Rational Functions and Partial Fractions

### 2.5.2 Integrating Partial Fractions

---

## Review Exercises

### Exercises for 2.1

1.  Find \\(\int 3(3x-5)^3\,dx\\).
2.  Find \\(\int 4v\sech^2(2v^2+1)\,dv\\).
3.  Find \\(\int \frac{2e^x}{e^x+3}\,dx\\).
4.  Find \\(\int 2t^3\sqrt{t^2+1}\,dt\\).
    (Hint: \\(2t^3=2t\cdot t^2\\).)
5.  Find \\(\int \frac{2(\ln s)^3}{s}\,ds\\).
6.  Find \\(\int \frac{3\sqrt{x}}{2(x^{3/2}+2)^2}\,dx\\).
7.  Find \\(\int \frac{\cos(1/y)}{y^2}\,dy\\).
8.  Compute \\(\int_0^{\pi/12} \sec(3\theta)\tan(3\theta)\,d\theta\\).
9.  Compute \\(\int_1^2 (6x+3)(x^2+x)^2\,dz\\).
10. Compute \\(\int_1^{\ln 2}\frac{e^z}{1+e^{2z}}\,dz\\).
11. Compute \\(\int_e^{e^2}\frac{1}{x\ln x}\,dx\\).
12. Use Substitution to find \\(\int\cot\theta\,d\theta\\).
13. Multiply by \\(\frac{\sec x+\tan x}{\sec x+\tan x}\\) and use
    Substitution to prove \\(\int\sec\theta\,d\theta=\ln|\sec x+\tan x|\\).

### Exercises for 2.2
