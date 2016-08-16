---
layout: page
title: "Part 1: Functions Defined by Derivatives and Integrals"
---

**(note: all videos are temporary placeholders, do not watch yet)**

---

## 1.1 Logarithms and Exponential Functions

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 7.1

### 1.1.1 The Natural Logarithm

<iframe width="560" height="315" src="https://www.youtube.com/embed/AmhDHRKGeJs" frameborder="0" allowfullscreen></iframe>

- Using integrals, we may rigorously define a logarithm.
- \\( \ln x=\int_1^x \frac{1}{t}\,dt \\) for all \\(x>0\\)
- \\( \frac{d}{dx}[\ln x] = \frac{1}{x} \\)
- **Example.**
  Use the definition \\( \ln x=\int_1^x \frac{1}{t}\,dt \\)
  to prove the property \\( \ln(ax) = \ln a + \ln x \\) for
  \\(a,x>0\\). (Hint: start by showing that the derivatives are the same.)

### 1.1.2 The Natural Number and Natural Exponential Function

<iframe width="560" height="315" src="https://www.youtube.com/embed/AmhDHRKGeJs" frameborder="0" allowfullscreen></iframe>

- Note that \\(a^p\\) has only been defined for when \\(p\in\mathbb Q\\).
- Since \\(f(x)=\ln x\\) is differentiable and 1-to-1, we can define
  \\(\exp x=f^{-1}(x)\\) to be its differentiable inverse.
- **Example.**
  Use the fact \\(\frac{d}{dx}[f^{-1}(x)]=\frac{1}{f'(f^{-1}(x))}\\)
  to prove that \\(\frac{d}{dx}[\exp x]=\exp x\\).
  (Hint: let \\(f(x)=\ln x,f'(x)=\frac{1}{x},f^{-1}(x)=\exp x\\).)
- Let \\(e=\exp 1\\). We'll see much later in the
  course why \\(e\approx 2.718\\).

### 1.1.3 General Logarithms and Exponential Functions

<iframe width="560" height="315" src="https://www.youtube.com/embed/AmhDHRKGeJs" frameborder="0" allowfullscreen></iframe>

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
  to prove the property \\( x = \log_b(b^x) \\).

### Exercises for 1.1

1.  Use the definition \\( \ln x=\int_1^x \frac{1}{t}\,dt \\)
    to prove that \\( \ln 1 = 0 \\).
2.  Use the definition \\( \ln x=\int_1^x \frac{1}{t}\,dt \\)
    to prove the property \\( \ln(x^p) = p\ln x \\) for \\(x>0\\)
    and \\(p\in\mathbb Q\\). (Hint:
    start by showing that the derivatives are the same.)
3.  We saw that \\(\frac{d}{dx}[e^x]=e^x\\).
    Describe infinitely many other functions \\(f(x)\\) such that
    \\(f'(x)=f(x)\\).
4.  Find formulas for the derivatives of \\( \log_b x \\) and
    \\( a^x \\).



---

## 1.2 Trigonometric Functions

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - (none)

### 1.2.1 Sine and Cosine

### 1.2.2 Geometric Properties



---

## 1.3 Hyperbolic Functions

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 7.3

### 1.3.1 Hyperbolic Sine and Cosine

### 1.3.2 Other Hyperbolic Functions

### 1.3.3 Derivatives and Integrals of Hyperbolic Functions
