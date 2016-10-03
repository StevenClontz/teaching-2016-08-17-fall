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
    diameter of the cylinder along the \\(x\\)-axis from \\(-2\\) to \\(2\\),
    and use the equation \\(x^2+y^2=2^2\\).
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
- **Example**
  Find the volume of the solid of revolution obtained by rotating the
  region bounded by \\(y=x\\) and \\(y=x^2\\) around the axis \\(y=2\\).

### 3.3.2 Rotation about Vertical Axes

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
7.  (Quiz, 3.1 material)
    Find the area between the curves \\(y=x^2\\) and \\(y=4\\).
    - \\(\frac{32}{3}\\)
    - \\(\frac{25}{4}\\)
    - \\(7\\)
8.  (Quiz)
    What integral is produced by the washer method for the
    volume of the solid of revolution obtained by rotating
    the region bounded by \\(y=x^2\\) and \\(y=4\\) around the
    \\(x\\)-axis?
    - \\(\pi\int_{-2}^2[(4)^2-(x^2)^2]\,dx\\)
    - \\(\pi\int_0^2(x^2-4)^2\,dx\\)
    - \\(\int_{-1}^1 2\sqrt{\pi}-y\sqrt{\pi}\,dy\\)
9.  (Quiz)
    What integral is produced by the washer method for the
    volume of the solid of revolution obtained by rotating
    the triangle with vertices \\((1,1)\\), \\((2,1)\\), \\((2,0)\\)
    around the axis \\(x=3\\)?
    - \\(\pi\int_0^1[(1+y)^2-(1)^2]\,dy\\)
    - \\(\int_1^2[\pi(2-y)^2-(3)^2]\,dy\\)
    - \\(\pi\int_1^3[(2)^2-(2+x)^2]\,dx\\)

[Solutions 1-3]({{site.baseurl}}public/solutions/3.3a.pdf)

[Solutions 4-6]({{site.baseurl}}public/solutions/3.3b.pdf)

[Solutions 7-9]({{site.baseurl}}public/solutions/3.3c.pdf)




---

## 3.4 The Cylindrical Shell Method

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 6.2

### 3.4.1 Rotation about Vertical Axes

<iframe width="560" height="315" src="https://www.youtube.com/embed/NrTsu8WYjPg" frameborder="0" allowfullscreen></iframe>

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

<iframe width="560" height="315" src="https://www.youtube.com/embed/xoACNK1trLA" frameborder="0" allowfullscreen></iframe>

- **Example**
  Find the volume of the solid of revolution obtained by rotating the
  region bounded by \\(y=0\\), \\(x=\pm1\\), \\(y=x^2+1\\) around the
  line \\(x=2\\).

### 3.4.2 Rotation about Horizontal Axes

<iframe width="560" height="315" src="https://www.youtube.com/embed/qeyp192xcF4" frameborder="0" allowfullscreen></iframe>

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
    region bounded by \\(y=4\\), \\(y=x^2-4x+4\\) around the
    \\(y\\)-axis.
3.  Find the volume of the solid of revolution obtained by rotating the
    region bounded by \\(x=y^2-1\\), \\(x=3\\) around the
    axis \\(x=-1\\).
4.  Find the volume of the solid of revolution obtained by rotating the
    triangle with vertices \\((4,2)\\), \\((2,6)\\), \\((0,6)\\)
    around the axis \\(y=2\\).
5.  Find the volume of the solid of revolution obtained by rotating the
    region bounded by \\(x=e\\), \\(y=2\\), \\(y=\ln x\\) around the
    \\(x\\)-axis.
6.  (Optional)
    Use the cylindrical shell method to reprove the volume formula
    for a sphere: \\(V=\frac{4}{3}\pi R^3\\).
7.  (Quiz)
    What integral is produced by the cylindrical shell method for the
    volume of the solid of revolution obtained by rotating
    the triangle with vertices \\((0,0),(2,0),(0,4)\\) around the
    \\(y\\)-axis?
    - \\(\pi\int_0^2(2x^2)(2x+4)\,dx\\)
    - \\(\int_{-4}^4(2\pi-y)\,dy\\)
    - \\(2\pi\int_0^2(x)(4-2x)\,dx\\)
8.  (Quiz)
    What integral is produced by the cylindrical shell method for the
    volume of the solid of revolution obtained by rotating
    the region bounded by \\(x=0,y=2,x=y^3\\) around the axis \\(y=-1\\)?
    - \\(2\pi\int_0^2(y+1)(y^3),dy\\)
    - \\(2\pi\int_8^0(y-1)(y^3+1)\,dy\\)
    - \\(2\pi\int_1^3(2x)^2(\sqrt[3]x)\,dx\\)

[Solutions 1-3]({{site.baseurl}}public/solutions/3.4a.pdf)

[Solutions 4-8]({{site.baseurl}}public/solutions/3.4b.pdf)




---

## 3.5 Work

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 6.5

### 3.5.1 Work by a Constant Force

<iframe width="560" height="315" src="https://www.youtube.com/embed/YYrV6D_KMI8" frameborder="0" allowfullscreen></iframe>

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

<iframe width="560" height="315" src="https://www.youtube.com/embed/23-AT2qLE1o" frameborder="0" allowfullscreen></iframe>

- If the force \\(F(x)\\) acting on an object varies with respect to the
  position \\(x\\) of the object, then work done in moving the object from
  \\(a\\) to \\(b\\) is defined by \\(W=\int_a^b F(x)\,dx\\).
- **Example** Find the work done in lifting a leaky bucket of water \\(1\\)
  meter off the ground if it weighs \\(4-3x^2\\) newtons when it is
  \\(x\\) meters above the ground.
- **Example** How much work is done in pulling up \\(20\\) feet of
  hanging chain if it weighs \\(1\\) pound per \\(4\\) feet?

<iframe width="560" height="315" src="https://www.youtube.com/embed/yjcRyJDj5dM" frameborder="0" allowfullscreen></iframe>

- **Example** Hooke's Law states that the force required to hold
  a stretched or compressed spring is directly proportional to its
  natural length. That is, \\(F(x)=kx\\) where \\(x\\) is the difference
  between the spring's natural length and its current length.
  If a spring has natural length \\(10\\) inches, and it requires
  \\(15\\) pounds of force to hold the spring at \\(13\\) inches,
  how much work is required to stretch the spring an additional
  \\(2\\) inches?

### 3.5.3 Work and Pumping Liquid

<iframe width="560" height="315" src="https://www.youtube.com/embed/682QxafIkv4" frameborder="0" allowfullscreen></iframe>

- To compute the work in pumping liquid, we proceed by computing a
  work differential \\(dW\\) for each infintesimal cross-section of liquid
  at height \\(y\\), and then evaluating \\(W=\int_{y=a}^{y=b} dW\\)
  where \\(y=a\\) is the lowest point of liquid and \\(y=b\\) is the
  highest.
- **Example** Assume salt water weighs \\(10,000\\) newtons per
  cubic meter. How much work is required to pump out a conical tank
  pointed downward
  of height \\(6\\) meters and radius \\(3\\) meters, if it is initially
  filled with \\(4\\) feet of salt water?

### Exercises for 3.5

1.  Estimate the work done in pushing a plow \\(6\\) meters through
    increasingly packed dirt; this movement requires \\(1\\) newton of force
    at the beginning, \\(5\\) newtons of force after \\(2\\) meters,
    and \\(9\\) netwons of force after \\(4\\) meters.
2.  Compute the exact amount of work done in pushing a plow \\(6\\) meters
    through increasingly packed dirt; this movement requires
    \\(F(x)=1+2x\\) newtons of force after \\(x\\) meters.
3.  Find the work done in lifting a leaky bucket from the ground to
    a height of four feet, assuming it weighs
    \\(25-x\\) pounds at \\(x\\) feet above the ground.
4.  A cable weighing \\(4\\) pounds per foot holds a \\(500\\) pound bucket of
    coal at the bottom of a \\(300\\) foot mine shaft. Show that the
    total work done in lifting the cable and bucket is
    \\(330,000\\) foot-pounds.
5.  Hooke's Law states that the force required to hold
    a stretched or compressed spring is directly proportional to its
    natural length. That is, \\(F(x)=kx\\) where \\(x\\) is the difference
    between the spring's natural length and its current length.
    Show that if a spring has natural length \\(20\\) cm, and it requires
    \\(25\\) newtons of force to hold the spring at \\(15\\) cm,
    then the work required to stretch the spring from its natural length
    to \\(26\\) cm is \\(90\\) N-cm.
6.  A uniformly weighted \\(100\\) foot rope weighs \\(50\\) pounds.
    Suppose it is fully extended into a well, tied to a leaky bucket of
    water. This bucket weighs \\(10\\) pounds and
    initially holds \\(30\\) pounds of water,
    but loses \\(1\\) pound of water every \\(2\\) feet. Show that
    the work done in lifting the rope and bucket is \\(4400\\) ft-lbs.
    (Hint: When does the bucket run out of water?)
7.  Assume salt water weighs \\(10\\) kilonewtons (kN) per cubic meter.
    A cylindrical tank with a radius of \\(3\\) meters and a height of
    \\(10\\) meters holds \\(8\\) meters of salt water. Show that
    the work required to pump out the salt water to the top of the tank
    is \\(4320\pi\\) kN-m (kJ).
8.  Assume salt water weighs \\(10000\\) newtons per cubic meter.
    A pyramid-shaped tank of height \\(4\\) meters is pointed upward,
    with a square base of side length \\(4\\) meters, and is completely
    filled with salt water. Show that the
    work done in completely pumping all the water in the tank up to the
    point of the pyramid is \\(10000\int_0^4(4-y)^3\,dy\\) J.
9.  (Optional)
    Assume that a cubic inch of Juicy Juice(TM) weighs \\(D\\) oz.
    Suppose a perfectly spherical coconut-shaped cup with radius \\(R\\)
    inches is completely filled with Juicy Juice(TM). Show that drinking
    the entire beverage using a straw which extends \\(S\\) inches above
    the top of the container requires
    \\(\frac{4}{3}D\pi R^3(R+S)\\) inch-ounces of work.
10. What is the work required to push a heavy box \\(3\\) meters over
    an irregular surface, assuming it requires \\(F(x)=3+2x-x^2\\) newtons
    of force to move at \\(x\\) meters?
    - \\(\frac{5}{3}\\) joules
    - \\(9\\) joules
    - \\(\frac{13}{3}\\) joules
11. Which of these integrals gives the work in ft-lbs
    required to pull up a hanging \\(30\\)-pound \\(15\\)-foot chain?
    - \\(\int_0^{15}(60-2x)\,dx\\)
    - \\(\int_0^{15x}30\,dy\\)
    - \\(\int_{15}^{30}(15+x)\,dx\\)
12. Which of these integrals gives the work in kN-m required to
    pump out all salt-water to the top of a cubical tank with side length
    \\(4\\) meters, if it is initially half-full? Assume the
    density of salt water is \\(10\\) kilonewtons per cubic meter.
    - \\(10\pi\int_0^4(16+8y+y^2)\,dy\\)
    - \\(\int_0^{16}(4-y)^3\,dy\\)
    - \\(160\int_0^2(4-y)\,dy\\)

[Solutions 1-6]({{site.baseurl}}public/solutions/3.5a.pdf)
[Solutions 7-12]({{site.baseurl}}public/solutions/3.5b.pdf)
