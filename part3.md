---
layout: page
title: "Part 3: Applications of Integrals"
---

---

## 3.1 Area Between Curves

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 5.6

### 3.1.1 Areas between Functions of \\(x\\)

<iframe width="560" height="315" src="https://www.youtube.com/embed/mUbUYjVmV8s" frameborder="0" allowfullscreen></iframe>

- Recall that \\(\int_a^b f(x)\,dx\\) is the net area between \\(y=f(x)\\)
  and \\(y=0\\).
- Let \\(f(x)\leq g(x)\\) for \\(a\leq x\leq b\\). We define the area
  between the curves \\(y=f(x)\\) and \\(y=g(x)\\) from \\(a\\) to \\(b\\)
  to be the integral \\(\int_a^b [g(x)-f(x)]\,dx\\).
- We call \\(y=f(x)\\) the bottom curve and \\(y=g(x)\\) the top curve.
- **Example** Find the area between the curves \\(y=2+x\\) and
  \\(y=1-\frac{1}{2}x\\) from \\(2\\) to \\(4\\).

<iframe width="560" height="315" src="https://www.youtube.com/embed/R1LwUMRhn6k" frameborder="0" allowfullscreen></iframe>

- **Example** Find the area bounded by the curves \\(y=x^2-4\\) and
  \\(y=8-2x^2\\).
- **Example** Prove that the area of a circle of radius \\(r\\) is
  \\(\pi r^2\\). (Hint: use the curves \\(y=\pm\sqrt{r^2-x^2}\\).)

### 3.1.2 Areas between Functions of \\(y\\)

<iframe width="560" height="315" src="https://www.youtube.com/embed/LLv__SGVqPM" frameborder="0" allowfullscreen></iframe>

- Areas between functions \\(f(y)\leq g(y)\\) may be found similarly,
  but in this case \\(x=f(y)\\) is the left curve and \\(x=g(y)\\) is
  the right curve.
- **Example** Find the area bounded by the curves \\(y=\sqrt{x}\\),
  \\(y=0\\), and \\(y=x-2\\).

### Exercises for 3.1

1.  Find the area between the curves \\(y=4\\) and \\(y=4x^3\\) from
    \\(-1\\) to \\(1\\).
2.  Find the area bounded by the curves \\(y=x^2-2x\\) and \\(y=x\\).
4.  Find the area bounded by the curves \\(y=\pm\sqrt{4-x}\\) and \\(x=3\\).
4.  Find the area bounded by the curves \\(y=0\\), \\(x=0\\), \\(y=1\\),
    and \\(y=\ln x\\).
5.  Use a definite integral to prove that the area of the
    triangle with vertices \\((0,0)\\), \\((b,0)\\),
    \\((0,h)\\) is \\(\frac{1}{2}bh\\).
6.  (Optional) Find the area of the ellipse \\(9x^2+16y^2=25\\).

[Solutions]({{site.baseurl}}public/solutions/3.1.pdf)

---

## 3.2 Volumes by Cross-Sectioning

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 6.1

### 3.2.1 Defining Volume with Integrals

<iframe width="560" height="315" src="https://www.youtube.com/embed/myniFisw1sY" frameborder="0" allowfullscreen></iframe>

- The volume of a solid defined between \\(x=a\\) to \\(x=b\\)
  with a cross-sectional area of \\(A(x)\\) at each \\(x\\)-value
  is defined to be \\(V=\int_a^b A(x)\,dx\\).

<iframe width="560" height="315" src="https://www.youtube.com/embed/XuRYovkZE-s" frameborder="0" allowfullscreen></iframe>

- Steps for solving such problems:
    1. Sketch the solid along the \\(x\\)-axis with a typical
       cross-section at some \\(x\\) value.
    2. Find the formula for \\(A(x)\\), and the minimal/maximal
       \\(x\\) values \\(a,b\\).
    3. Evaluate \\(V=\int_a^b A(x)\,dx\\).
- **Example** Show that the volume of a pyramid with a square base
  of sidelength \\(2\\) and height \\(3\\) is \\(4\\) cubic units.

### 3.2.2 Circular Cross-Sections

<iframe width="560" height="315" src="https://www.youtube.com/embed/Dhrsn_Lg3Ac" frameborder="0" allowfullscreen></iframe>

- In the case that all cross-sections are circular, we may replace
  \\(A(x)\\) with \\(\pi[R(x)]^2\\), where \\(R(x)\\) is the radius
  of the circular cross-section at that \\(x\\) value.
- **Example** Prove that a cone of radius \\(r\\) and height \\(h\\)
  has volume \\(V=\frac{1}{3}\pi r^2 h\\).

### Exercises for 3.2

1.  Find the volume of a solid located between \\(x=-1\\) and \\(x=2\\)
    with cross-sectional area \\(A(x)=x^2+1\\) for all \\(-1\leq x\leq 2\\).
2.  Find the volume of a solid located between \\(x=0\\) and \\(x=1\\)
    whose cross-sections are parallelograms with base length \\(b(x)=x+1\\)
    and height \\(h(x)=x^2+1\\) for all \\(0\leq x\leq 1\\).
4.  Find the volume of a wedge cut from a circular cylinder
    with radius \\(2\\), sliced out at a \\(45^\circ\\) angle from the
    diameter of its base. (Hint: Sketch the
    diameter of the cylinder along the \\(x\\)-axis from \\(-2\\) to \\(2\\).
    The cross-sections will be isosceles triangles.)
5.  Prove that the volume of a sphere with radius \\(r\\) is
    \\(V=\frac{4}{3}\pi r^3\\). (Hint: Draw a diameter of the sphere
    on the \\(x\\)-axis from \\(-r\\) to \\(r\\), and use the equation
    \\(x^2+y^2=r^2\\).)
5.  (Optional)
    Find the volume of the solid whose base is the region
    \\(0\leq y\leq 4-x^2\\) and whose
    cross-sections are
    equilateral triangles perpendicular to the \\(x\\)-axis.

[Solutions]({{site.baseurl}}public/solutions/3.2.pdf)



---

## 3.3 The Washer Method

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 6.1

[Lecture Notes]({{site.baseurl}}public/solutions/3.3examples.pdf)

### 3.3.1 Rotation about Horizontal Axes

<iframe width="560" height="315" src="https://www.youtube.com/embed/NrTsu8WYjPg" frameborder="0" allowfullscreen></iframe>

- Many solids may be described as revolutions of two-dimensional regions.
  Such solids have washer-shaped cross-sections.
- To obtain the volume of a solid of revolution about a horizontal axis,
  identify the outer radius \\(R(x)\\) and inner radius \\(r(x)\\) for each
  \\(x\\)-value, the leftmost \\(a\\) and rightmost \\(b\\) \\(x\\)-values
  in the region and use the formula
  \\(V=\int_a^b \pi([R(x)]^2-[r(x)]^2)\,dx\\).
- **Example**
  Find the volume of the solid of revolution obtained by rotating the
  triangle with vertices \\((0,0)\\), \\((2,2)\\), \\((2,4)\\) around
  the \\(x\\)-axis.

<iframe width="560" height="315" src="https://www.youtube.com/embed/xoACNK1trLA" frameborder="0" allowfullscreen></iframe>

- **Example**
  Find the volume of the solid of revolution obtained by rotating the
  region bounded by \\(y=x\\) and \\(y=x^2\\) around the axis \\(y=2\\).

### 3.3.2 Rotation about Vertical Axes

<iframe width="560" height="315" src="https://www.youtube.com/embed/qeyp192xcF4" frameborder="0" allowfullscreen></iframe>

- When the axis of revolution is vertical, simply use functions of \\(y\\)
  rather than \\(x\\), and the bottommost \\(c\\) and topmost \\(d\\)
  \\(y\\)-values:
  \\(V=\int_c^d \pi([R(y)]^2-[r(y)]^2)\,dy\\).
- **Example**
  Find the volume of the solid of revolution obtained by rotating the
  region bounded by \\(y=0\\), \\(x=1\\), \\(y=\sqrt{x}\\) around the
  axis \\(x=-1\\).

### Exercises for 3.3

1.  Find the volume of the solid of revolution obtained by rotating the
    triangle with vertices \\((3,0)\\), \\((3,3)\\), \\((0,3)\\)
    around the \\(x\\)-axis.
2.  Find the volume of the solid of revolution obtained by rotating the
    region bounded by \\(y=x^2\\), \\(y=2x\\) around the axis
    \\(y=-2\\).
3.  Consider the region in the \\(xy\\) plane
    satisfying \\(|x|\leq\frac{\pi}{2}\\) and \\(|y|\leq\cos x\\).
    Find the volume of the solid of revolution obtained by rotating
    this region around the axis \\(y=3\\).
4.  Find the volume of the solid of revolution obtained by rotating the
    triangle with vertices \\((0,0)\\), \\((2,0)\\), \\((2,1)\\) around
    the axis \\(x=4\\).
5.  Find the volume of the solid of revolution obtained by rotating the
    region bounded by \\(x+y=1\\), \\(y=\ln x\\), \\(y=1\\) around
    the \\(y\\)-axis.
6.  (Optional)
    Find the volume of the solid of revolution obtained by rotating the
    triangle with vertices \\((-\sqrt 2,0)\\), \\((0,\sqrt 2)\\),
    \\((\sqrt 2,0)\\) around the axis \\(y=\sqrt 2-x\\).
    (Hint: Translate the region and its axis so that it has a horizontal
    or vertical axis of revolution.)




---

## 3.4 The Cylindrical Shell Method

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 6.2

### 3.4.1 Rotation about Vertical Axes

- As an alternative to the washer method, one may consider
  "cylindrical shell" cross-sections instead.
- The lateral surface area of a cylinder is given by \\(2\pi rh\\).
- For a vertical axis of revolution, identify the radius \\(r(x)\\) and
  height \\(h(x)\\) of a cylindrical shell, identify the leftmost \\(a\\) and
  rightmost \\(b\\) \\(x\\)-values of the region, and use the formula
  \\(V=\int_a^b 2\pi r(x)h(x)\,dx\\).
- **Example**
  Find the volume of the solid of revolution obtained by rotating the
  region bounded by \\(y=0\\), \\(x=1\\), \\(y=\sqrt{x}\\) around the
  line \\(x=-1\\).
- **Example**
  Find the volume of the solid of revolution obtained by rotating the
  region bounded by \\(y=0\\), \\(x=\pm1\\), \\(y=x^2+1\\) around the
  line \\(x=2\\).

### 3.4.2 Rotation about Horizontal Axes

- When the axis of revolution is horiztonal, simply use functions of \\(y\\)
  rather than \\(x\\), and the bottommost \\(c\\) and topmost \\(d\\)
  \\(y\\)-values:
  \\(V=\int_c^d 2\pi r(y)h(y)\,dy\\).
- **Example**
  Find the volume of the solid of revolution obtained by rotating the
  triangle with vertices \\((-1,2)\\), \\((0,1)\\), \\((2,2)\\) around
  the \\(x\\)-axis.

### Exercises for 3.4

1.  Find the volume of the solid of revolution obtained by rotating the
    triangle with vertices \\((0,2)\\), \\((1,0)\\), \\((1,2)\\)
    around the axis \\(x=2\\).
2.  Find the volume of the solid of revolution obtained by rotating the
    region bounded by \\(y=4\\), \\(y=x^2-4x+4\\), \\(x=2\\) around the
    \\(y\\)-axis.
3.  Find the volume of the solid of revolution obtained by rotating the
    region bounded by \\(x=y^2-1\\), \\(x=3\\) around the
    axis \\(x=-1\\).
4.  Find the volume of the solid of revolution obtained by rotating the
    triangle with vertices \\((3,0)\\), \\((3,3)\\), \\((0,3)\\)
    around the \\(x\\)-axis.
5.  Find the volume of the solid of revolution obtained by rotating the
    region bounded by \\(x=e\\), \\(y=2\\), \\(y=\ln x\\) around the
    \\(x\\)-axis.
6.  (Optional)
    Use the cylindrical shell method to reprove the volume formula
    for a sphere: \\(V=\frac{4}{3}\pi R^3\\).



---

## 3.5 Work

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 6.5

### 3.5.1 Work by a Constant Force

- In physics, the work \\(W\\) done by a force of constant magnitude \\(F\\)
  over a displacement \\(d\\) by the formula \\(W=Fd\\).
- **Example** Calculate the work done by a crane in lifting a \\(3000\\) pound
  wrecking ball \\(25\\) feet.
- **Example** Estimate the work done in lifting a leaky bucket of water
  \\(1\\) meter off the ground if it weighs approximately
  \\(4\\) newtons on the ground,
  \\(3.8\\) newtons at \\(25\\) cm,
  \\(3.5\\) newtons at \\(50\\) cm,
  and \\(2.3\\) newtons at \\(75\\) cm.

### 3.5.2 Work by a Variable Force

- If the force \\(F(x)\\) acting on an object varies with respect to the
  position \\(x\\) of the object, then work done in moving the object from
  \\(a\\) to \\(b\\) is defined by \\(W=\int_a^b F(x)\,dx\\).
- **Example** Find the work done in lifting a leaky bucket of water \\(1\\)
  meter off the ground if it weighs \\(4-3x^2\\) newtons when it is
  \\(x\\) meters above the ground.
- **Example** How much work is done in pulling up \\(20\\) feet of
  hanging chain if it weighs \\(1\\) pound per \\(4\\) feet?
- **Example** Hooke's Law states that the force required to hold
  a stretched or compressed spring is directly proportional to its
  natural length. That is, \\(F(x)=kx\\) where \\(x\\) is the difference
  between the spring's natural length and its current length.
  If a spring has natural length \\(10\\) inches, and it requires
  \\(15\\) pounds of force to hold the spring at \\(13\\) inches,
  how much work is required to stretch the spring an additional
  \\(2\\) inches?

### 3.5.3 Work and Pumping Liquid

- To compute the work in pumping liquid, we proceed by computing a
  work differential \\(dW\\) for each infintesimal slab of liquid
  at height \\(y\\), and then evaluating \\(W=\int_{y=a}^{y=b} dW\\)
  where \\(y=a\\) is the lowest point of liquid and \\(y=b\\) is the
  highest.
- **Example** Assume salt water weighs \\(10,000\\) newtons per
  cubic meter. How much work is required to pump out a conical tank
  of height \\(6\\) meters and radius \\(3\\) meters, if it is initially
  filled with \\(4\\) feet of salt water?
