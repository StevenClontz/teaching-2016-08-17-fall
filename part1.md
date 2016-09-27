---
layout: page
title: "Part 1: Functions Defined by Derivatives and Integrals"
---

<!-- TODO in general, grouping in integrals -->

---

## 1.1 Logarithms and Exponential Functions

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 7.1 (review: 1.5,1.6)

### 1.1.1 The Natural Logarithm

<iframe width="560" height="315" src="https://www.youtube.com/embed/7d0uTAlv0vo" frameborder="0" allowfullscreen></iframe>

- Using integrals, we may rigorously define a logarithm.
- \\( \ln x=\int_1^x \frac{1}{t}\,dt \\) for all \\(x>0\\)
- \\( \frac{d}{dx}[\ln x] = \frac{1}{x} \\) and \\(\ln 1 = 0\\)
- **Example.**
  Use the definition \\( \ln x=\int_1^x \frac{1}{t}\,dt \\)
  to prove the property \\( \ln(ax) = \ln a + \ln x \\) for
  \\(a,x>0\\). (Hint: start by showing that the derivatives are the same.)
- This allows us to express an indefinite integral for \\(1/x\\):
  \\(\int\frac{1}{x}\,dx=\ln|x|+C\\). (Note the absolute value.)
- **Example.**
  Find \\(\int \frac{3}{x^2}-\frac{2}{x}+1+4x^2\,dx\\).

### 1.1.2 The Natural Number and Natural Exponential Function

<!-- TODO fix video to use arrow inverse notation -->

<iframe width="560" height="315" src="https://www.youtube.com/embed/QqxdUCwim5Y" frameborder="0" allowfullscreen></iframe>

- Note that \\(a^p\\) has only been defined for when \\(p\in\mathbb Q\\).
- Since \\(f(x)=\ln x\\) is differentiable and 1-to-1, we can define
  \\(\exp x=f^{\leftarrow}(x)\\) to be its differentiable inverse.
- **Example.**
  Use the fact
  \\(\frac{d}{dx}[f^{\leftarrow}(x)]=\frac{1}{f'(f^{\leftarrow}(x))}\\)
  to prove that \\(\frac{d}{dx}[\exp x]=\exp x\\).
  (Hint: let \\(f(x)=\ln x,f'(x)=\frac{1}{x},f^{\leftarrow}(x)=\exp x\\).)
- Let \\(e=\exp 1\\). We'll see much later in the
  course why \\(e\approx 2.718\\).

### 1.1.3 General Logarithms and Exponential Functions

<iframe width="560" height="315" src="https://www.youtube.com/embed/u4ww4xnToOI" frameborder="0" allowfullscreen></iframe>

- Since \\(\exp x\\) is defined for all real numbers, we may define
  \\(a^x = \exp(x\ln a)\\) for all \\(a>0\\) and \\(x\in\mathbb R\\).
  Note that \\(e^x = \exp x\\).
- **Example.**
  Use the definition \\(a^x = \exp(x\ln a)\\) and
  property \\(\ln(abc)=\ln a + \ln b + \ln c\\) to show that
  \\(2^3 = 2\times2\times2\\).
- Define \\( \log_b x = \frac{\ln x}{\ln b} \\) for \\(b>1\\).
- **Example.**
  Use the definitions
  \\( \log_b x = \frac{\ln x}{\ln b} \\) and \\(b^x = \exp(x\ln b)\\)
  to prove the property \\( x = \log_b(b^x) \\). (That is,
  \\(\log_b x\\) and \\(b^x\\) are inverse functions.)

### Exercises for 1.1

1.  Use the definition \\( \ln x=\int_1^x \frac{1}{t}\,dt \\)
  to prove the property \\( \ln(x^p) = p\ln x \\) for \\(x>0\\)
  and \\(p\in\mathbb Q\\). (Hint: start by showing that both sides share
  the same derivative.)
2.  Find \\(\int \frac{6}{x^3}+\frac{2}{x}-3x\,dx\\).
3.  Find \\(\int \frac{6x^4-x^2+4}{2x^3}\,dx\\).
4.  We saw that \\(\frac{d}{dx}[e^x]=e^x\\).
  Describe infinitely many other functions \\(f(x)\\) such that
  \\(f'(x)=f(x)\\).
5.  Find \\(\frac{d}{dx}[\frac{1}{x}+3e^x]\\).
6.  Prove the following derivative formulas:
    \\( \frac{d}{dx}[\log_b x]=\frac{1}{x\ln b} \\) and
    \\( \frac{d}{dx}[a^x]=a^x \ln a \\).
7.  (Quiz) Integrate \\(\int 3x^4+3e^x-\frac{4}{x}\,dx\\).
    - \\(12x^3-3e^x+4\ln\|x\|+C\\)
    - \\(\frac{3}{5}x^5+3e^x-4\ln\|x\|+C\\)
    - \\(\frac{3}{4}x^5+3xe^{x-1}-\frac{4}{x^2}+C\\)
    - None of the above
8.  (Quiz) Differentiate \\(f(x)=\ln(x^2)+e^{x^3}\\).
    - \\(f'(x)=\frac{2}{x}+3x^2e^{x^3}\\)
    - \\(f'(x)=2x\ln(x^2)+x^3e^{x^3-1}+C\\)
    - \\(f'(x)=\frac{2x}{x^2}+e^{x^3}\\)
    - None of the above


[Solutions]({{site.baseurl}}public/solutions/1.1.pdf)



---

## 1.2 Trigonometric Functions

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - none (review: 1.3)

### 1.2.1 Sine and Cosine

<iframe width="560" height="315" src="https://www.youtube.com/embed/qiVorZ9PNdg" frameborder="0" allowfullscreen></iframe>

- Similar to how \\(\ln x\\) and \\(e^x\\) are defined by integrals, we use
  derivatives to define the trigonometric functions.
- Define \\(f(x)=\sin x\\) to be the unique solution to the differential equation
  (initial value problem) \\(f^{\prime\prime}(x)=-f(x),f'(0)=1,f(0)=0\\).
- Define \\(\cos(x)\\) to be the derivative \\(\frac{d}{dx}[\sin x]\\).
- **Example**
  Prove that \\(\frac{d}{dx}[\cos x]=-\sin x\\).
- The other four trig functions are then defined as usual as quotients
  of \\(\sin x\\) and \\(\cos x\\).

### 1.2.2 Geometric Properties

<iframe width="560" height="315" src="https://www.youtube.com/embed/COGs6o__pL0" frameborder="0" allowfullscreen></iframe>

- The geometric properties of \\(\sin x\\) and \\(\cos x\\) come from the
  fact that they satisfy the Pythagorean identity:
  \\([\sin x]^2+[\cos x]^2=1\\).
- **Example**
  Prove the Pythagorean identity. (Hint: start by showing that both sides share
  the same derivative.)



### Exercises for 1.2

1.  Show that \\(f(x)=\cos(x)\\) is a solution to the differential equation
    \\(f^{\prime\prime}(x)=-f(x),f'(0)=0,f(0)=1\\).
2.  Show that \\(f(x)=\sin(3x)\\) is a solution to the differential equation
    \\(f^{\prime\prime}(x)=-9f(x),f'(0)=3,f(0)=0\\).
3.  Find a solution to the differential equation
    \\(f^{\prime\prime}(x)=-f(x),f'(0)=0,f(0)=4\\).
4.  Prove that if \\( x\\) is an angle where
    \\(\sin x = -\frac{5}{13}\\), then \\(\cos x\\) is either
    \\(\frac{12}{13}\\) or \\(-\frac{12}{13}\\). (Hint: use the Pythagorean
    identity.)
5.  (Optional) <!-- TODO make nonoptional -->
    Find a solution to the differential equation
    \\(f^{\prime\prime}(x)=-4f(x),f'(0)=6,f(0)=0\\).
6.  (Optional)
    Prove that \\(-1\leq\sin x\leq 1\\) and \\(-1\leq\cos x\leq 1\\).
    (Hint: use the Pythagorean identity.)


[Solutions]({{site.baseurl}}public/solutions/1.2.pdf)

---

## 1.3 Hyperbolic Functions

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 7.3

### 1.3.1 Hyperbolic Sine and Cosine

<iframe width="560" height="315" src="https://www.youtube.com/embed/J78Ido7MOxE" frameborder="0" allowfullscreen></iframe>

- Exponential functions are used to define the hyperbolic functions,
  which behave like trigonometric functions in many ways.
    - \\(\sinh x = \frac{e^x-e^{-x}}{2}\\)
    - \\(\cosh x = \frac{e^x+e^{-x}}{2}\\)
- **Example** Evaluate \\(\sinh(0)\\) and \\(\cosh(0)\\).
- **Example** Evaluate \\(\cosh(\ln 4)\\).
- **Example** Prove that \\(\sinh(2x)=2\sinh(x)\cosh(x)\\).

\\(\newcommand{\sech}{\mathrm{sech}\,}\\)
\\(\newcommand{\csch}{\mathrm{csch}\,}\\)

### 1.3.2 Other Hyperbolic Functions

<iframe width="560" height="315" src="https://www.youtube.com/embed/5pHJkJoPSiA" frameborder="0" allowfullscreen></iframe>

- The other hypberbolic functions are defined the same way their
  trig counterparts are, and have similar properties.
    - \\(\tanh x = \frac{\sinh x}{\cosh x} = \frac{e^x-e^{-x}}{e^x+e^{-x}}\\)
    - \\(\coth x = \frac{\cosh x}{\sinh x} = \frac{e^x+e^{-x}}{e^x-e^{-x}}\\)
    - \\(\sech x = \frac{1}{\cosh x}=\frac{2}{e^x+e^{-x}}\\)
    - \\(\csch x = \frac{1}{\sinh x}=\frac{2}{e^x-e^{-x}}\\)
- **Example** Evaluate \\(\sech(-\ln 2)\\).
- **Example** Prove that \\(\tanh^2(x)=1-\sech^2(x)\\).


### 1.3.3 Derivatives and Integrals of Hyperbolic Functions

<iframe width="560" height="315" src="https://www.youtube.com/embed/8WSn1tyUE90" frameborder="0" allowfullscreen></iframe>

- Their derivatives also behave similarly.
    - \\(\frac{d}{dx}[\sinh x] = \cosh x\\)
    - \\(\frac{d}{dx}[\cosh x] = \sinh x\\)
    - \\(\frac{d}{dx}[\tanh x] = \sech^2 x\\)
    - \\(\frac{d}{dx}[\coth x] = -\csch^2 x\\)
    - \\(\frac{d}{dx}[\sech x] = -\sech x\tanh x\\)
    - \\(\frac{d}{dx}[\csch x] = -\csch x\coth x\\)
- **Example**
  Use their definitions to prove that \\(\frac{d}{dx}[\cosh x]=\sinh x\\).
- **Example**
  Use their definitions to prove that \\(\frac{d}{dx}[\coth x]=\csch^2 x\\).
- **Example**
  Compute \\(\frac{d}{dx}[\sinh(2x)+\coth(x^2)]\\).
- Their integral formulas may be found by just reversing the equations.
    - \\(\int \cosh x\,dx = \sinh x + C \\)
    - \\(\int \sinh x\,dx = \cosh x + C \\)
    - \\(\int \sech^2 x\,dx = \tanh x + C \\)
    - \\(\int \csch^2 x\,dx = -\coth x + C \\)
    - \\(\int\sech x\tanh x\,dx = -\sech x + C \\)
    - \\(\int\csch x\coth x\,dx = -\csch x + C \\)
- **Example**
  Find \\(\int 4\csch^2 x-3\sinh x\,dx\\).


### Exercises for 1.3

1.  Evaluate \\(\sinh(\ln 6)\\).
3.  Prove that \\(\cosh (2x) = \cosh^2 x + \sinh^2 x\\).
3.  Prove that \\(\cosh^2 x - \sinh^2 x = 1\\).
4.  Evaluate \\(\tanh(\ln 3)\\).
5.  Simplify \\(\sinh(x)\coth(x)\cosh(x)-\frac{1}{\csch^2(x)}\\).
    (Hint: convert everything to \\(\sinh x\\) and \\(\cosh x\\).)
6.  Prove that \\(\frac{d}{dx}[\sinh x] = \cosh x\\).
7.  Prove that \\(\frac{d}{dx}[\sech x] = -\sech x\tanh x\\).
    (Hint: use the fact that \\(\frac{d}{dx}[\cosh x] = \sinh x\\).)
8.  Compute \\(\frac{d}{dx}[\tanh(3x)-\sech(\ln x)]\\).
9.  Find \\(\int 3\csch x\coth x - 2\sinh x\,dx\\).
10. (Optional)
    Let \\(\sinh^{\leftarrow}(x)\\) be the inverse function of
    \\(\sinh(x)\\). Use the facts
    \\(\frac{d}{dx}[f^{\leftarrow}(x)]=\frac{1}{f'(f^{\leftarrow}(x))}\\)
    and \\(\cosh^2 x-\sinh^2 x = 1\\) to prove that
    \\(\frac{d}{dx}[\sinh^{\leftarrow}(x)]=\frac{1}{\sqrt{1+x^2}}\\).
11. (Optional)
    Prove that \\(\sinh^{\leftarrow}(x)=\ln(\sqrt{x^2+1}+x)\\).
12. (Quiz)
    Evaluate \\(\cosh(\ln 2)\\).
    - \\(\frac{3}{5}\\)
    - \\(\frac{2}{3}\\)
    - \\(\frac{5}{4}\\)
13. (Quiz)
    Differentiate \\(f(x)=\tanh(x^2)-\cosh(2x+1)\\).
    - \\(f'(x)=-\sech(x^2)\tanh(x^2)+\sinh(2x+1)+2\\)
    - \\(f'(x)=2x\sech^2(x^2)-2\sinh(2x+1)\\)
    - \\(f'(x)=\frac{1}{1+x^4}+2\sinh(2x+1)\\)

[Solutions 1-11]({{site.baseurl}}public/solutions/1.3.pdf)
[Solutions 12,13]({{site.baseurl}}public/solutions/1.3quiz.pdf)
---

## Review Exercises

The exercises are now located with their respective notes.
