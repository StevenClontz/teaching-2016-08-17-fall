---
layout: page
title: "Part 4: Parametric Equations and Polar Coordiantes"
---

---

## 4.1 Planar Parametrizations

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 10.1

### 4.1.1 Parametric Equations

<iframe width="560" height="315" src="https://www.youtube.com/embed/pMrEt_KGGAA" frameborder="0" allowfullscreen></iframe>

- If \\(x(t),y(t)\\) are both defined as functions of \\(t\\) over some
  interval \\(I\\) of real numbers, then the set of points
  \\(\\{(x(t),y(t)):t\in I\\}\\) is the parametric curve with a
  system of parametric equations \\(x(t),y(t)\\). If \\(I\\) is omitted,
  then it is assumed that \\(t\\) belongs to the set of all real numbers.
- **Example**
  Plot the parametric curve \\(x=\cos t,y=\sin t\\) for
  \\(0\leq t\leq 2\pi\\), first by using a chart of \\(t,x,y\\) values,
  then by expressing the curve as an equation of \\(x,y\\).
- **Example**
  Show that the systems of parametric equations \\(x_0=t,y_0=t^2\\) and
  \\(x_1=2t-2,y_1=4t^2-8t+4\\) share the same parametric curve.

### 4.1.2 Parametrizing Curves Defined by Functions

<iframe width="560" height="315" src="https://www.youtube.com/embed/4EXKmRsfWww" frameborder="0" allowfullscreen></iframe>

- The curve \\(y=f(x)\\) where \\(x\\) belongs to the interval \\(I\\)
  may be easily parametrized left-to-right
  by the system of parametric equations
  \\(x=t,y=f(t)\\) where \\(t\\) also belongs to \\(I\\).
- **Example**
  Give a system of parametric equations for the curve \\(y=\ln x\\)
  from \\((1,0)\\) to \\((e^2,2)\\).

### 4.1.3 Parametrizing Line Segments <!-- TODO add circles -->

<iframe width="560" height="315" src="https://www.youtube.com/embed/Fp_Bee3vSMs" frameborder="0" allowfullscreen></iframe>

- The line segment joining the points \\((x_0,y_0),(x_1,y_1)\\) may
  be parametrized by \\(x=x_0+(x_1-x_0)t,y=y_0+(y_1-y_0)t\\) where
  \\(0\leq t\leq 1\\).
- **Example**
  Give a system of parametric equations for the line segment joining
  \\((2,-3)\\) and \\((-1,4)\\).
- **Example**
  Give two different systems of parametric equations for the portion of the
  line \\(y=3x-2\\) between \\(x=-1\\) and \\(x=2\\).
- The full line may be obtained with the same equations
  by allowing \\(t\\) to range over all real numbers.

### Exercises for 4.1

1.  Plot the parametric curve \\(x=2-t^2,y=2t^2\\) for
    \\(0\leq t\leq 3\\), first by using a chart of \\(t,x,y\\) values,
    then by expressing the curve as an equation of \\(x,y\\).
2.  Plot the parametric curve \\(x=3^t,y=3^{-t}\\) for
    \\(-\infty<t<\infty\\), first by using a chart of \\(t,x,y\\) values,
    then by expressing the curve as an equation of \\(x,y\\).
3.  Show that the systems of parametric equations \\(x_0=t+2,y_0=e^2e^t\\) and
    \\(x_1=\ln t,y_1=t\\) share the same parametric curve.
    Then plot that curve.
4.  Give a system of parametric equations for the curve \\(y=\cosh x\\)
    from \\((-\ln 2,5/4)\\) to \\((\ln 2,5/4)\\).
5.  Give a system of parametric equations for the line segment joining
    \\((0,-4)\\) and \\((3,5)\\).
6.  Give a system of parametric equations for the line segment joining
    \\((1,2)\\) and \\((-3,3)\\).
7.  Give two different systems of parametric equations for the portion of the
    line \\(y=4-3x\\) between \\(x=-2\\) and \\(x=3\\).
8.  (Optional)
    Let \\(a<b\\).
    Find a system of parametric equations which parametrizes the planar
    curve \\(y=f(x)\\) *right-to-left* from \\(x=b\\) to \\(x=a\\).

[Solutions]({{site.baseurl}}public/solutions/4.1.pdf)

---

## 4.2 Applications of Parametrizations

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 10.2, 6.3, 6.4

### 4.2.1 Parametric Formula for \\(dy/dx\\)

<iframe width="560" height="315" src="https://www.youtube.com/embed/I4Rpho1e99E" frameborder="0" allowfullscreen></iframe>

- Let \\(y\\) be a function of \\(x\\), and suppose its
  curve is parametrized by the equations \\(x(t),y(t)\\). Then by
  the Chain Rule, \\(\frac{dy}{dt}=\frac{dy}{dx}\frac{dx}{dt}\\)
  at each point where all of these functions is differentiable.
- **Example**
  Find the line tangent to the curve parametrized by
  \\(x=\tan t,y=\sec t,-\frac{\pi}{2}<t<\frac{\pi}{2}\\)
  at the point \\((1,\sqrt 2)\\).
- **Example**
  Find the point on the parametric curve \\(x=\ln t,y=t+\frac{1}{t},t>0\\)
  which has a horizontal tangent line.

### 4.2.2 Arclength

<iframe width="560" height="315" src="https://www.youtube.com/embed/jagdtq9s3s0" frameborder="0" allowfullscreen></iframe>

- Suppose a curve \\(C\\) is defined parametrically by one-to-one functions
  \\(x(t),y(t)\\) on \\(a\leq t\leq b\\), where
  \\(\frac{dx}{dt},\frac{dy}{dt}\\) are continuous and never simultaneously
  zero. Then the length of \\(C\\) is defined to be
  \\(
    L
  =
    \int_{t=a}^{t=b}ds
  =
    \int_{t=a}^{t=b}\sqrt{dx^2+dy^2}
  =
    \int_a^b\sqrt{(\frac{dx}{dt})^2+(\frac{dy}{dt})^2}\,dt
  \\).
- **Example** Use the arclength formula to find the length of the
  line segment joining \\((-2,3)\\) and \\((2,0)\\).

<iframe width="560" height="315" src="https://www.youtube.com/embed/Z14bNRMmfIc" frameborder="0" allowfullscreen></iframe>

- **Example** Find the perimeter of the curve parametrized by
  \\(x=\sin^3 t,y=\cos^3 t,0\leq t\leq 2\pi\\).

### 4.2.3 Surface Areas from Revolution

<iframe width="560" height="315" src="https://www.youtube.com/embed/cbsSOm2Hkzc" frameborder="0" allowfullscreen></iframe>

- Suppose a smooth curve \\(C\\)
  is defined parametrically by one-to-one functions
  \\(x(t),y(t)\\) on \\(a\leq t\leq b\\), with \\(y(t)\geq 0\\).
  Then the area of the surface of revolution obtained by rotating
  \\(C\\) about the \\(x\\)-axis is given by
  \\(2\pi\int_{t=a}^{t=b}y(t)\,ds\\).


<iframe width="560" height="315" src="https://www.youtube.com/embed/XZ5Og5B9E-Y" frameborder="0" allowfullscreen></iframe>

- **Example** Find the area of the surface of revolution obtained by
  rotating the portion of the parabola \\(y=x^2\\) from \\((0,0)\\)
  to \\((4,2)\\) around the \\(x\\)-axis.

### Exercises for 4.2

1.  Find the line tangent to the curve parametrized by
    \\(x=t^2,y=t^3\\)
    at the point where \\(t=-2\\).
1.  Show that the line tangent to the curve parametrized by
    \\(x=3\sin t,y=3\cos t\\)
    at the point \\((\frac{3}{2},\frac{3\sqrt 3}{2})\\)
    has the equation \\(y=2\sqrt{3}-\frac{1}{\sqrt 3}x\\).
    (Hint: \\(\frac{1}{\sqrt 3}\frac{3}{2}=\frac{\sqrt 3}{2}\\).)
1.  Find the point on the parametric curve
    \\(x=2t^2+1,y=t^4-4t\\)
    which has a horizontal tangent line.
1.  Use the arclength formula to find the length of the
    line segment joining \\((-2,6)\\) and \\((3,-6)\\).
1.  Use the arclength formula to prove that the circumference of a
    circle of radius \\(R\\) is \\(2\pi R\\).
1.  Show that the arclength of the curve parameterized by \\(x=\cos 2t\\),
    \\(y=2t+\sin 2t\\), \\(0\leq t\leq \pi/2\\) is \\(4\\).
    (Hint: \\(1+\cos 2t=2\cos^2 t\\).)
1.  Find the area of the surface obtained by rotating the curve parameterized
    by \\(x=\cos t,y=2+\sin t,0\leq t\leq \pi/2\\) around the \\(x\\)-axis.
1.  Use the parametric equations \\(x=t,y=t,0\leq t\leq 1\\) to
    show that the surface area of the cone of height \\(1\\) and radius
    \\(1\\) is \\(\pi(\sqrt 2+1)\\). (Hint: Don't forget to add the area
    of the base of the cone.)
1.  (Optional)
    Show that the surface area of the cone of height \\(H\\) and radius
    \\(R\\) is \\(\pi R(\sqrt{H^2+R^2}+R)\\).
1.  (Quiz)
    Find the point on the parametric curve
    \\(x=e^{3t}+5,y=e^{2t}-2t+1\\)
    which has a horizontal tangent line.
    - \\((e^3,e^2)\\)
    - \\((6,2)\\)
    - \\((5,e-1)\\)
    - *(Note: the quiz given in class had (6,0) as a choice by mistake,
      making the correct answer D.)*
2.  (Quiz)
    Which of these integrals gives the arclength of the curve
    \\(y=x^2-3x+4\\) between \\((1,2)\\) and \\((3,4)\\)?
    - \\(\int_1^3\sqrt{4t^2-12t+10}\,dt\\)
    - \\(\int_2^4\sqrt{2t+3t^2}\,dt\\)
    - \\(\int_0^1(4+2t)\,dt\\)

[Solutions]({{site.baseurl}}public/solutions/4.2.pdf)

---

## 4.3 Polar Coordinates

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 10.3

### 4.3.1 Definition of Polar Coordinates

<iframe width="560" height="315" src="https://www.youtube.com/embed/1tjeJmTmBbg" frameborder="0" allowfullscreen></iframe>

- The polar coordinate \\(p(r,\theta)\\) is defined to be Cartesian
  coordinate \\((r\cos\theta,r\sin\theta)\\).
- **Example** Plot the polar coordinates
  \\(p(2,\pi/3),p(\sqrt{2},3\pi/4),p(-2,4\pi/3),p(4,11\pi/6)\\).
- Note that every polar coordinate \\(p(r,\theta)\\) is equal to
  \\(p(r,\theta+k\pi)\\) for all even integers \\(k\\), and equal to
  \\(p(-r,\theta+k\pi)\\) for all odd integers \\(k\\).

### 4.3.2 Equations Relating Polar and Cartesian Coordinates

<iframe width="560" height="315" src="https://www.youtube.com/embed/ar4rY_uDrbY" frameborder="0" allowfullscreen></iframe>

- Polar and Cartesian coordinates may be related by the equations
  \\(x=r\cos\theta\\), \\(y=r\sin\theta\\), \\(x^2+y^2=r^2\\),
  and \\(\tan\theta=\frac{y}{x}\\).
- **Example**
  Convert the Cartesian coordinate \\((-2\sqrt3,2)\\) into a polar
  coordinate.

<iframe width="560" height="315" src="https://www.youtube.com/embed/pIXfMdVHxNk" frameborder="0" allowfullscreen></iframe>

- **Example**
  Convert the polar equation \\(r=\frac{1}{\sin\theta-\cos\theta}\\),
  \\(\pi/4<\theta<5\pi/4\\)
  into a Cartesian equation.
- **Example**
  Convert the Cartesian equation \\((x-2)^2+y^2=4\\)
  into a polar equation.

### 4.3.3 Common Polar Equations <!-- TODO add r=a\sin(\theta)-->

<iframe width="560" height="315" src="https://www.youtube.com/embed/edC-bfH6xh8" frameborder="0" allowfullscreen></iframe>

- The equation \\(r=R\\) is a circle centered at the origin of radius
  \\(R\\).
- The equation \\(\theta=\alpha\\) is the line passing through the origin
  at the angle \\(\\alpha\\).
- The equation \\(r\cos\theta=a\\) is the vertical line \\(x=a\\).
- The equation \\(r\sin\theta=b\\) is the horizontal line \\(y=b\\).
- **Example** <!-- TODO fix minor issue in video -->
  Sketch the region where \\(0<\csc\theta\leq r\leq 2\\).
- The equations \\(r=a\pm a\cos\theta\\) and \\(r=a\pm a\sin\theta\\)
  are known as cardioids.
- **Example**
  Sketch the cardioid \\(r=4-4\sin\theta\\).

### Exercises for 4.3

1.  Convert the polar coordinates
    \\(p(\sqrt 3,2\pi/3),p(\sqrt 2,\pi/4),p(2,7\pi/6),p(-\sqrt 3,-\pi/3)\\)
    to Cartesian and plot them in the \\(xy\\) plane.
2.  Convert the Cartesian coordinates
    \\((4,-4),(-\frac{3}{2},-\frac{\sqrt 3}{2})\\)
    into polar coordinates.
3.  Convert the polar equation \\(r=\frac{5}{\sqrt{25-9\sin^2\theta}}\\)
    into a Cartesian equation. Name the curve.
4.  Convert the Cartesian equation
    \\(1-\frac{y}{x^2+y^2}=\frac{3}{\sqrt{x^2+y^2}}\\) into a polar equation.
4.  Convert the Cartesian equation for the line
    \\(y=\frac{x}{\sqrt 3}\\) into a polar equation.
4.  Sketch the region where \\(0< 3\sec\theta\leq r\leq 6\cos\theta\\).
    (Hint: Completing the square in \\(x^2-6x+y^2=0\\) yields
    \\((x-3)^2+y^2=9\\).)
4.  Sketch the cardioid \\(r=3+3\sin\theta\\).
4.  Sketch the cardioids \\(r=1+\cos\theta\\) and \\(r=1-\cos\theta\\).
    At what points do they intersect?
4.  (OPTIONAL)
    Sketch the "three-leaved rose" \\(r=\sin 3\theta\\).
1.  (QUIZ)
    Which of these polar coordinates gives the point \\((-\sqrt3,1)\\)?
    - \\(p(\sqrt2,3\pi/4)\\)
    - \\(p(\sqrt3,\pi/3)\\)
    - \\(p(2,5\pi/6)\\)
1.  (QUIZ)
    Convert the circle \\(x^2+(y-4)^2=16\\) into a polar equation.
    - \\(r=16\\)
    - \\(r=8\sin\theta\\)
    - \\(r=12\cos^2\theta-4\sin^2\theta\\)
1.  (QUIZ)
    Which of these equations gives the curve drawn below?
    - \\(r=3+3\cos\theta\\)
    - \\(r=3-3\sin\theta\\)
    - \\(r=3\tan\theta\\)

![Cardioid]({{site.baseurl}}public/cardioid.gif)

[Solutions 1-5]({{site.baseurl}}public/solutions/4.3a.pdf)

[Solutions 6-12]({{site.baseurl}}public/solutions/4.3b.pdf)



---

## 4.4 Areas and Lengths using Polar Coordinates

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 10.5

### 4.4.1 Area Between Polar Curves

<iframe width="560" height="315" src="https://www.youtube.com/embed/Gz0vRIShjRk" frameborder="0" allowfullscreen></iframe> <!-- TODO drop f(\theta) -->

- The area of the circle sector of angle \\(\theta\\) is given by
  \\(A=\pi r^2\times\frac{\theta}{2\pi}=\frac{1}{2}r^2\theta\\).
- Therefore the area bounded by \\(\alpha\leq\theta\leq\beta\\),
  \\(r=f(\theta)\\) is
  \\(A=\frac{1}{2}\int_\alpha^\beta(f(\theta))^2\,d\theta\\).
- **Example**
  Find the area bounded by the cardioid \\(r=2+2\sin\theta\\).

<iframe width="560" height="315" src="https://www.youtube.com/embed/VvmPhO5nY00" frameborder="0" allowfullscreen></iframe>

- To obtain the area where \\(f(\theta)\leq r\leq g(\theta)\\),
  where \\(f\\) is an inside curve and \\(g\\) is an outside curve,
  find the clockwise angle \\(\alpha\\) and counter-clockwise angle
  \\(\beta\\) where they intersect, and use
  \\(A=\frac{1}{2}\int_\alpha^\beta((g(\theta))^2-(f(\theta))^2)\,d\theta\\).
- **Example**
  Find the area outside the circle \\(x^2+y^2=1\\) and inside the
  cardioid \\(r=1-\cos\theta\\).

### 4.4.2 Length of a Polar Curve

<iframe width="560" height="315" src="https://www.youtube.com/embed/TZAQB6AkB7w" frameborder="0" allowfullscreen></iframe>

- The polar curve \\(r=f(\theta)\\) where \\(\alpha\leq\theta\leq\beta\\)
  may be parametrized by \\(x=f(\theta)\cos\theta,y=f(\theta)\sin\theta\\)
  with the same bounds, using \\(\theta\\) in place of \\(t\\) as the
  parameter.
- Therefore its length is given by
  \\(L=\int_\alpha^\beta\sqrt{
      (\frac{dx}{d\theta})^2+(\frac{dy}{d\theta})^2
  }\,d\theta\\)
  which simplifies to
  \\(L=\int_\alpha^\beta\sqrt{
      (f(\theta))^2+(f'(\theta))^2
  }\,d\theta\\).
- **Example**
  Show that the circumference of the circle of radius \\(R\\) is \\(2\pi R\\).
- **Example**
  Find the circumference of the spiral \\(r=\theta^2\\) from
  \\(p(0,0)\\) to \\(p(5,\sqrt 5)\\).

### Exercises for 4.4

1.  Find the area inside \\(r=\cos2\theta\\) where \\(0\leq\theta\leq\pi/4\\).
1.  Find the area bounded by the cardioid \\(r=1-\cos\theta\\).
2.  Sketch the region where \\(\|x\|\leq y\leq\sqrt{1-x^2}+1\\).
    Show that its area is \\(\frac{\pi}{2}+1\\).
    (Hint: Show that this is the area inside \\(r=2\sin\theta\\)
    where \\(\pi/4\leq\theta\leq3\pi/4\\).)
1.  Find the length of one rotation of the spiral \\(r=e^\theta\\).
1.  Use the polar arclength formula to show that the circumference of the
    circle \\(r=4\sin\theta\\) is \\(4\pi\\).
1.  Show that the length of the cardioid \\(r=2+2\cos\theta\\) is
    \\(\int_0^{2\pi}\sqrt{8+8\cos\theta}\,d\theta=16\\).
1.  (OPTIONAL)
    Prove that if \\(x=f(\theta)\cos\theta\\) and \\(y=f(\theta)\sin\theta\\)
    then
\\(\int_\alpha^\beta\sqrt{
    (\frac{dx}{d\theta})^2+(\frac{dy}{d\theta})^2
}\,d\theta
=\int_\alpha^\beta\sqrt{
    (f(\theta))^2+(f'(\theta))^2
}\,d\theta\\).
1.  (QUIZ)
    Which of these integrals is the area of the cardioid \\(r=4+4\sin\theta\\)?
    - \\(\int_0^{2\pi}(8+16\sin\theta+8\sin^2\theta)\,d\theta\\)
    - \\(\int_0^{\pi/2}(16+16\sin^2\theta)\,d\theta\\)
    - \\(\int_0^{\pi}6\sin^2\theta\,d\theta\\)
1.  (QUIZ)
    Which of these integrals is the length of the curve \\(r=\cos^2\theta\\)
    where \\(0\leq\theta\leq\pi/2\\)?
    - \\(\int_0^{\pi/2}4\sin\theta\sqrt{1-\cos^2\theta}\,d\theta\\)
    - \\(\int_0^{\pi/2}(\cos^4\theta-\pi)\,d\theta\\)
    - \\(\int_0^{\pi/2}\cos\theta\sqrt{1+3\sin^2\theta}\,d\theta\\)

[Solutions 1-7]({{site.baseurl}}public/solutions/4.4a.pdf)
[Solutions 8-9]({{site.baseurl}}public/solutions/4.4b.pdf)
