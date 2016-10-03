---
layout: page
title: "Part 2: Advanced Integration Techniques"
---

\\(\newcommand{\sech}{\operatorname{sech}}\\)
\\(\newcommand{\csch}{\operatorname{csch}}\\)
\\(\newcommand{\inverse}[1]{#1^{\leftarrow}}\\)

---

<!-- TODO add guessing method -->

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

<!-- TODO require knowing all basic trig antiderivatives -->

### 2.1.3 Antiderivatives of Trigonometric Functions

<iframe width="560" height="315" src="https://www.youtube.com/embed/bHkxJk6bBAc" frameborder="0" allowfullscreen></iframe>

- The antiderivatives of the basic trig functions (besides sine/cosine)
  may be derived by using Substitution.
- **Example**
  Use Substitution to find \\(\int\tan\theta\,d\theta\\).
- **Example**
  Prove that \\(\int\csc x\,dx = -\ln|\csc x+\cot x|+C\\).

### Exercises for 2.1

1.  Find \\(\int 3(3x-5)^3\,dx\\).
2.  Find \\(\int 4e^{r-7}\,dr\\).
3.  Find \\(\int 4v\sech^2(2v^2+1)\,dv\\).
4.  Find \\(\int \frac{2e^x}{e^x+3}\,dx\\).
5.  Find \\(\int 2t^3\sqrt{t^2+1}\,dt\\).
    (Hint: \\(2t^3=2t\cdot t^2\\).)
6.  Find \\(\int \frac{2(\ln s)^3}{s}\,ds\\).
7.  Find \\(\int \frac{3\sqrt{x}}{2(x^{3/2}+2)^2}\,dx\\).
8.  Find \\(\int \frac{\cos(1/y)}{y^2}\,dy\\).
9.  Compute \\(\int_0^{\pi/12} \sec(3\theta)\tan(3\theta)\,d\theta\\).
10. Compute \\(\int_1^2 (6x+3)(x^2+x)^2\,dx\\).
11. Compute \\(\int_{\ln 3}^{\ln 8}e^z\sqrt{1+e^z}\,dz\\).
12. Compute \\(\int_e^{e^2}\frac{1}{x\ln x}\,dx\\).
13. Use Substitution to find \\(\int\cot\theta\,d\theta\\).
14. Multiply by \\(\frac{\sec x+\tan x}{\sec x+\tan x}\\) and use
    Substitution to prove \\(\int\sec x\,dx=\ln|\sec x+\tan x|+C\\).
15. (Quiz)
    Find \\(\int 3t^5(t^3+3)^2\,dt\\).
    - \\(\frac{1}{4}t^4-4t^3+C\\)
    - \\(\frac{1}{4}(t^3+3)^4-(t^3+3)^3+C\\)
    - \\(\frac{1}{2}(t^3+3)^2+4(t^3+3)^3+C\\)
16. (Quiz)
    Evaluate \\(\int_0^1 x^2e^{2x^3}\,dx\\).
    - \\(\frac{1}{6}e^2-\frac{1}{6}\\)
    - \\(\frac{1}{4}e^2-\frac{1}{4}e\\)
    - \\(\frac{1}{3}e-\frac{1}{3}\\)

[Solutions 1-8]({{site.baseurl}}public/solutions/2.1a.pdf)

[Solutions 9-16]({{site.baseurl}}public/solutions/2.1b.pdf)

---

<!-- TODO make this section last -->

## 2.2 Integration by Parts

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 8.1

    <!-- TODO make improvements for cycling -->

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

<iframe width="560" height="315" src="https://www.youtube.com/embed/evAqb25XkHk" frameborder="0" allowfullscreen></iframe>

- When using parts to evaluate definite integrals, do not forget
  to apply the bounds of integration to the entire integral.
- **Example**
  Find \\(\int_0^1 s^2e^s\,ds\\).

### 2.2.3 Antiderivatives of Logarithms

<iframe width="560" height="315" src="https://www.youtube.com/embed/JFCKIopecZI" frameborder="0" allowfullscreen></iframe>

- Integrating logarithms is based on integration by parts.
- **Example**
  Use Integration by Parts to find \\(\int\ln x\,dx\\).

### Exercises for 2.2

1.  Find \\(\int 3x\cosh(x)\,dx\\).
2.  Find \\(\int te^{2t}\,dt\\).
3.  Find \\(\int y^2\sin(y)\,dy\\).
4.  Find \\(\int 4x\sec^2(x)\,dx\\).
    (Hint: recall \\(\int\tan\theta\,d\theta=\ln|\sec\theta|+C\\).)
5.  Find \\(\int e^{3w}\sinh(w)\,dw\\).
6.  Find \\(\int \sin(2x)\cos(4x)\,dx\\).
7.  Compute \\(\int_1^e x\ln x\,dx\\).
8.  (Optional)
    Find \\(\int x^4e^x\,dx\\).
9.  (Optional)
    Prove \\(
      \int \cos^{n+2} x\,dx
    =
      \frac{\cos^{n+1} x\sin x}{n+2}+\frac{n+1}{n+2}\int\cos^n x\,dx
    \\). (Hint: take the derivative of both sides.)
10. (Optional)
    Find \\(\int \cos^4 x\,dx\\) using the above formula.
11. (Quiz)
    Find \\(\int x\cosh x\,dx\\).
    - \\(x\sinh x-\cosh x+C\\)
    - \\(x^2\sinh x+2\cosh x+C\\)
    - \\(x\cosh x+3x\sinh x+C\\)
12. (Quiz)
    Find \\(\int e^\theta\sin\theta\,d\theta\\).
    - \\(\frac{e^\theta\sin\theta+e^\theta\cos\theta}{3}+C\\)
    - \\(-\frac{e^\theta\cos\theta}{4}+C\\)
    - \\(\frac{e^\theta\sin\theta-e^\theta\cos\theta}{2}+C\\)

[Solutions 1-5]({{site.baseurl}}public/solutions/2.2a.pdf)

[Solutions 6-12]({{site.baseurl}}public/solutions/2.2b.pdf)

---

## 2.3 Trigonometric Integrals

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 8.2

### 2.3.1 Integrating Products of Sine and Cosine

<iframe width="560" height="315" src="https://www.youtube.com/embed/Cd4WfFc-xq8" frameborder="0" allowfullscreen></iframe>

- To integrate a function of the form \\(\sin^m x\cos^n x\\) where
  at least one of \\(m,n\\) is odd, use these identities to
  substitute \\(u=\sin x,du=\cos x\,dx\\) or
  \\(u=\cos x,du=-\sin x\,dx\\).
    - \\(\cos^2 x=1-\sin^2 x\\)
    - \\(\sin^2 x=1-\cos^2 x\\)
- **Example**
  Find \\(\int\sin^3\theta\cos^4\theta\,d\theta\\).
- **Example**
  Find \\(\int\sin^2(2y)\cos^5(2y)\,dy\\).

<iframe width="560" height="315" src="https://www.youtube.com/embed/fHQnlVD915E" frameborder="0" allowfullscreen></iframe>

- If both \\(m,n\\) are even, then one of these identities must be used:
    - \\(\cos^2 x=\frac{1}{2}+\frac{1}{2}\cos(2x)\\)
    - \\(\sin^2 x=\frac{1}{2}-\frac{1}{2}\cos(2x)\\)
- **Example**
  Find \\(\int\cos^2 x\,dx\\).
- **Example**
  Find \\(\int\sin^2 z\cos^2 z\,dz\\).


<!-- TODO make improvements for identifying secant/tangent -->

### 2.3.2 Integrating Products of Secant and Tangent

<iframe width="560" height="315" src="https://www.youtube.com/embed/XpV_R8prU4A" frameborder="0" allowfullscreen></iframe>

- To integrate a function of the form \\(\sec^m x\tan^n x\\),
  use these identities to
  substitute \\(u=\tan x,du=\sec^2 x\,dx\\) or
  \\(u=\sec x,du=\sec x\tan x\,dx\\).
    - \\(\tan^2 x=\sec^2 x-1\\)
    - \\(\sec^2 x=\tan^2 x+1\\)
- **Example**
  Find \\(\int\tan^3\theta\sec^3\theta\,d\theta\\).
- **Example**
  Find \\(\int\sec^4 x\tan^5 x\,dx\\).

### Exercises for 2.3

1.  Find \\(\int\sin^4 x\cos^3 x\,dx\\).
2.  Find \\(\int\sin^5 \theta\cos^2 \theta\,d\theta\\).
3.  Find \\(\int\sin^2 x\,dx\\).
4.  Find \\(\int\cos^4 y\,dy\\).
5.  Find \\(\int\tan^2 t\sec^4 t\,dt\\).
6.  (Optional)
    Use integration by parts with cycling to prove
    \\(
      \int\sec^3 x\,dx
    =
      \frac{1}{2}\sec x\tan x+\frac{1}{2}\ln|\sec x+\tan x|+C
    \\).
    (Hint: \\(\int\sec x\tan^2 x\,dx=\int\sec x(\sec^2 x-1)\,dx\\).)

[Solutions]({{site.baseurl}}public/solutions/2.3.pdf)


---

## 2.4 Trigonometric Substitution

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 8.3

### 2.4.1 Substituting for \\(a+bx^2\\)

<iframe width="560" height="315" src="https://www.youtube.com/embed/qBsX-ha-weU" frameborder="0" allowfullscreen></iframe>

- To eliminate factors of the form \\(a+bx^2\\) from an integral,
  use the substitution \\(a+bx^2=a+a\tan^2\theta=a\sec^2\theta\\)
  with \\(-\pi/2<\theta<\pi/2\\).
- **Example**
  Find \\(\int\frac{z^2}{4+9z^2}\,dz\\).


<iframe width="560" height="315" src="https://www.youtube.com/embed/O2HkhWSws6A" frameborder="0" allowfullscreen></iframe>

- **Example**
  Compute \\(\int_0^2\frac{1}{\sqrt{16+4x^2}}\,dx\\).
  (Recall \\(\int\sec\theta\,d\theta=\ln|\sec\theta+\tan\theta|+C\\).)

### 2.4.2 Substituting for \\(a-bx^2\\)

<iframe width="560" height="315" src="https://www.youtube.com/embed/lOM8Pwz-2X4" frameborder="0" allowfullscreen></iframe>

- To eliminate factors of the form \\(a-bx^2\\) from an integral,
  use the substitution \\(a-bx^2=a-a\sin^2\theta=a\cos^2\theta\\)
  with \\(-\pi/2\leq\theta\leq\pi/2\\).
- Note that this is only valid when \\(\|x\|\leq\sqrt{a/b}\\),
  which is guaranteed when \\(a-bx^2\\) is under a square root.
- **Example**
  Find \\(\int(4-25s^2)^{-3/2}\,ds\\).

<iframe width="560" height="315" src="https://www.youtube.com/embed/V6t5KjcUJVQ" frameborder="0" allowfullscreen></iframe>

- **Example**
  Find \\(\int\frac{x^3}{\sqrt{1-4x^2}}\,dx\\).

### 2.4.3 Substituting for \\(bx^2-a\\)

<iframe width="560" height="315" src="https://www.youtube.com/embed/u0-PinsRqXc" frameborder="0" allowfullscreen></iframe>

- To eliminate factors of the form \\(bx^2-a\\) from an integral,
  use the substitution \\(bx^2-a=a\sec^2\theta-a=a\tan^2\theta\\)
  with \\(0\leq\theta<\pi/2\\).
- Note that this is only valid when \\(x\geq\sqrt{a/b}\\),
  which will be assumed in our problems.
- **Example**
  Prove \\(\int\frac{1}{x\sqrt{x^2-1}}\,dx=\inverse\sec x+C\\)
  where \\(x>1\\).
- **Example**
  Find \\(\int\frac{\sqrt{y^2-16}}{y}\,dy\\) where \\(y\geq 4\\).


### 2.4.4 Using Inverse Trigonometric Antiderivatives

<iframe width="560" height="315" src="https://www.youtube.com/embed/r-umlF8ZNQk" frameborder="0" allowfullscreen></iframe>

- Sometimes, a simpler substiution may be combined with the following
  antiderivatives to obtain a solution more elegantly.
    - \\(\int\frac{1}{1+x^2}\,dx=\inverse\tan x+C\\).
    - \\(\int\frac{1}{\sqrt{1-x^2}}\,dx=\inverse\sin x + C\\).
    - \\(\int\frac{1}{x\sqrt{x^2-1}}\,dx=\inverse\sec x+C\\)
      where \\(x>1\\).
- **Example**
  Find \\(\int\frac{3}{\sqrt{9-x^2}}\,dx\\) without using a
  trigonometric substitution.

### Exercises for 2.4

1.  Find \\(\int\frac{2}{\sqrt{1+4z^2}}\,dz\\).
    (Recall \\(\int\sec\theta\,d\theta=\ln|\sec\theta+\tan\theta|+C\\).)
2.  Find \\(\int\frac{x^3}{9+x^2}\,dx\\).
    (Recall \\(\int\tan\theta\,d\theta=\ln|\sec\theta|+C\\).)
3.  Find \\(\int \frac{4}{(1-y^2)^{3/2}}\,dy\\).
4.  Find \\(\int\frac{2x^3}{\sqrt{9-x^2}}\,dx\\).
5.  Prove \\(\int\frac{1}{\sqrt{1-x^2}}\,dx=\inverse\sin x+C\\).
6.  Find \\(\int\frac{\sqrt{x^2-16}}{x}\,dx\\) where \\(x\geq 4\\).
7.  Find \\(\int\frac{1}{\sqrt{4t^2-1}}\,dt\\) where \\(t>\frac{1}{2}\\).
8.  Find \\(\int\frac{2}{\sqrt{1-4x^2}}\,dx\\) without a
    trigonometric substitution.
9.  (Optional)
    Find \\(\int\frac{2}{4+9x^2}\,dx\\) without a
    trigonometric substitution.
10. (Quiz)
    Find \\(\int \frac{1}{\sqrt{9+y^2}}\,dy\\).
    (Recall \\(\int\sec\theta\,d\theta=\ln\|\sec\theta+\tan\theta\|+C\\).)
    - \\(\ln\|\sqrt{1+\frac{1}{9}y^2}+\frac{y}{3}\|+C\\).
    - \\(\sin^{\leftarrow}(\frac{y}{9})+C\\)
    - \\(\ln(\sqrt{9+\frac{1}{9}y^2})+C\\)
    - (Note: the quiz given in class had a typo:
      \\(\int \frac{1}{\sqrt{9-y^2}}\,dy\\), making
      \\(\inverse\sin(\frac{y}{3})+C\\) or
      "None of the Above" the correct solution. The full solution below
      is for the version without a typo.)
11. (Quiz)
    Find \\(\int \frac{1}{x\sqrt{4x^2-1}}\,dy\\) where \\(x>\frac{1}{2}\\).
    - \\(\tan^{\leftarrow}(4x^2-1)+\ln\|x\|+C\\)
    - \\(\sec^{\leftarrow}(2x)+C\\)
    - \\(\ln\|x+\sqrt{4x^2-1}\|+C\\)

[Solutions 1-5]({{site.baseurl}}public/solutions/2.4a.pdf)

[Solutions 6-11]({{site.baseurl}}public/solutions/2.4b.pdf)



---

## 2.5 Integrating with Partial Fractions

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 8.4

### 2.5.1 Rational Functions and Partial Fractions

<!-- TODO generalize to ax+r,etc -->

<iframe width="560" height="315" src="https://www.youtube.com/embed/EmSIKDf_qug" frameborder="0" allowfullscreen></iframe>

- A function of the form \\(\frac{f(x)}{g(x)}\\) where \\(f,g\\) are
  both polynomials is called rational.
- The rational function \\(\frac{f(x)}{(x+r)^m}\\) may be split into
  the partial fractions
  \\(\frac{A_1}{x+r}+\frac{A_2}{(x+r)^2}+\dots+\frac{A_m}{(x+r)^m}\\),
  provided the degree of the numerator is less than the denominator.
- **Example**
  Expand \\(\frac{2x^2-7x+6}{(x-2)^3}\\) using partial fractions.


<iframe width="560" height="315" src="https://www.youtube.com/embed/CgpzFKX6ZeY" frameborder="0" allowfullscreen></iframe>

- The rational function \\(\frac{f(x)}{(x^2+px+q)^n}\\) (where
  \\(x^2+px+q\\) is irreducible) may be split into
  the partial fractions
  \\(
    \frac{B_1x+C_1}{x^2+px+q}+
    \frac{B_2x+C_2}{(x^2+px+q)^2}+
    \dots+
    \frac{B_mx+C_m}{(x^2+px+q)^n}
  \\),
  provided the degree of the numerator is less than the denominator.
- **Example**
  Expand \\(\frac{3x^2+2x+4}{x^4+2x^2+1}\\) using partial fractions.

<iframe width="560" height="315" src="https://www.youtube.com/embed/GqlkMqLmYcs" frameborder="0" allowfullscreen></iframe>

- When the denominator is a product of \\((x+r)^m\\) and
  \\((x^2+px+q)^n\\) terms, simply sum up the appropriate
  partial fractions for each factor.
- **Example**
  Describe the partial fractions which expand the rational function
  \\(\frac{f(x)}{(x+3)^3(x^2-2x+3)^2}\\).

### 2.5.2 Integrating Partial Fractions

<iframe width="560" height="315" src="https://www.youtube.com/embed/3LLOuOnOoEg" frameborder="0" allowfullscreen></iframe>

- Expanding rational functions using partial fractions allows us
  to integrate.
- **Example** Find \\(\int\frac{2x^2+5x-9}{(x-1)(x+1)(x-2)}\,dx\\).

<iframe width="560" height="315" src="https://www.youtube.com/embed/JvSzxVuQsoQ" frameborder="0" allowfullscreen></iframe>

- **Example** Find \\(\int\frac{4y^2+14y+15}{y^3+4y^2+5y}\,dy\\).

<iframe width="560" height="315" src="https://www.youtube.com/embed/tfO4BQojv_w" frameborder="0" allowfullscreen></iframe>

- If the numerator has degree greater than or equal to the denominator,
  you will need to use long polynomial division to break down the
  rational function first.
- **Example** Find \\(\int\frac{2t^3+t^2+3t+2}{(1+t)(1+t^2)}\,dt\\).

### Exercises for 2.5

1.  Expand \\(\frac{4x^2+16x+17}{(x+2)^3}\\) using partial fractions.
2.  Expand \\(\frac{-y^2+2y-4}{(y^2+4)^2}\\) using partial fractions.
3.  Expand \\(\frac{3r^3+r^2+3}{r^4+3r^2}\\) using partial fractions.
4.  Find \\(\int\frac{3z+2}{z^2+2z+1}\,dz\\).
5.  Find \\(\int\frac{3x^2+35}{x^3+5x}\,dx\\).
6.  Find \\(\int\frac{2v^3+4v^2+4v+2}{v^2+2v}\,dv\\).
7.  (Optional) Find \\(\int\frac{2x^3+6x^2+4x+2}{(x+1)^2(x^2+1)}\,dx\\).
8.  (Quiz)
    Which of the following describes the expansion of
    \\(\frac{f(t)}{(t+1)^2(t^2+9)}\\) using partial fractions?
    (Assume \\(f(t)\\) is a polynomial of degree less than 4.)
    - \\(\frac{At+B}{t+1}+\frac{C}{t^2+1}+\frac{D}{t^2+9}\\).
    - \\(\frac{A}{t}+\frac{Bt+C}{(t+1)^2}+\frac{D}{t+3}+\frac{E}{t^2+9}\\)
    - \\(\frac{A}{t+1}+\frac{B}{(t+1)^2}+\frac{Ct+D}{t^2+9}\\)
9.  (Quiz)
    Find \\(\int \frac{-x^2+6x-3}{(x+3)(x^2+1)}\,dx\\).
    - \\(-3\ln\|x+3\|+\ln\|x^2+1\|+C\\)
    - \\(\frac{3}{x^2+9}+2\ln(x^2+1)+C\\)
    - \\(2\ln(x+3)-\tan^{\leftarrow}(x^2+1)+C\\)

[Solutions 1-4]({{site.baseurl}}public/solutions/2.5a.pdf)

[Solutions 5-9]({{site.baseurl}}public/solutions/2.5b.pdf)

---

## 2.6 Strategies for Integration

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - Review of 5.5, 8.1, 8.2, 8.3, 8.4

### 2.6.1 Identifying Appropriate Integration Strategies

- When encountering an integration problem, it's useful to spot
  certain traits which can identify the best integration method
  to apply. The following list isn't fool-proof, but checking these
  in order can help you identify likely techniques for integration.
    1. Use algebra to simplify the integrand first, if possible.
       Split up sums into separate integrals as necessary.
    2. Is the integrand a constant multiple of a known derivative?
       If so, simply integrate using the constant multiple rule.
    3. Is the integral of the form \\(\int cf(g(x))g'(x)\,dx\\):
       a nested function along with (a constant multiple of)
       its derivative?
       If so, use integration by substitution with \\(u=g(x)\\).
    4. Is the integrand a rational function (a fraction of two polynomials)?
       If so, try the method of partial fractions
       to expand the integrand algebraically.
    5. Does the integrand include only trigonometric functions?
       Use trig identities to allow for a direct substitution.
    6. Does the integrand include expressions of the form \\(a+bx^2\\),
       \\(a-bx^2\\), or \\(bx^2-a\\)? Use the method of trigonometric
       substitution to simplify.
    7. Is the integrand the product of two functions? Integration by
       parts may produce a more manageable integral.
    8. At this point, check to make sure you didn't miss a possibility
       above. Otherwise, you may need to use a combination of techniques
       from the above to proceed.

 <iframe width="560" height="315" src="https://www.youtube.com/embed/3pL_XEYmFp8" frameborder="0" allowfullscreen></iframe>

- **Example** Find \\(\int\sinh x\sqrt{1+\cosh x}\,dx\\).
- **Example** Find \\(\int 2ze^{3z}\,dz\\).
- **Example** Find \\(\int\sin^2 \theta+\cos^2 \theta\,d\theta\\).
- **Example** Find \\(\int\frac{5x^2+12}{x^3+4x}\,dx\\).

<iframe width="560" height="315" src="https://www.youtube.com/embed/0_lntllVxZ4" frameborder="0" allowfullscreen></iframe>

- **Example** Find \\(\int3\sec y\tan y-\frac{1}{1+y^2}\,dy\\).
- **Example** Find \\(\int\frac{1}{\sqrt{4-9t^2}}\,dt\\).
- **Example** Find \\(\int\sin^2 x\cos^3 x\,dx\\).

### Exercises for 2.6

1.  Find \\(\int(x^2-1)(x^2+1)\,dx\\).
1.  Find \\(\int\frac{1}{\sqrt{9+z^2}}\,dz\\). (Recall
    \\(\int\sec\theta\,d\theta=\ln\|\sec\theta+\tan\theta\|+C\\).)
1.  Find \\(\int 6y^2e^{y^3}\,dy\\).
1.  Find \\(\int 3x\sin(4x)\,dx\\).
1.  Find \\(\int\sec^3 \theta\tan^3 \theta\,d\theta\\).
1.  Find \\(\int\frac{5x-5}{x^2-3x-4}\,dx\\).
1.  Find \\(\int \frac{3}{2}\sqrt{t}-\frac{1}{t\sqrt{t^2-1}}\,dt\\).
8.  (Optional)
    Find \\(\int e^x\sqrt{1-e^{2x}}\,dx\\).
    (Hint: \\(\sin(2\theta)=2\sin\theta\cos\theta\\).)

[Solutions]({{site.baseurl}}public/solutions/2.6.pdf)

---

## Review Exercises

The exercises are now located with their respective notes.
