# Solutions: Quadratic Equations - Fundamentals

This document provides detailed solutions to the questions presented in the `qbp-fundamentals.md` file.

---

## Question 1: What is a Root?

Consider the equation $x^2 - 5x + 6 = 0$.

**Q1.1: If you plug in $x=2$, does the equation hold?**
- **Solution:** Substitute $x = 2$ into the equation:
  $$2^2 - 5(2) + 6 = 4 - 10 + 6 = 0$$
  Yes, the equation holds. Therefore, $x=2$ is a root.

**Q1.2: What about $x=3$?**
- **Solution:** Substitute $x = 3$ into the equation:
  $$3^2 - 5(3) + 6 = 9 - 15 + 6 = 0$$
  Yes, the equation holds. Therefore, $x=3$ is also a root.

**Q1.3: Can a quadratic equation have 3 distinct roots? Why or why not?**
- **Solution:** No. A quadratic equation is a polynomial equation of degree 2. According to the **Fundamental Theorem of Algebra**, a polynomial of degree $n$ has exactly $n$ roots (counting multiplicity). Thus, a quadratic equation can have at most 2 distinct roots.

---

## Question 2: The Method of Completing the Square

Take the general form $ax^2 + bx + c = 0$.

**Q2.1: Divide the whole equation by $a$.**
- **Solution:** Dividing $ax^2 + bx + c = 0$ by $a$ (where $a \neq 0$):
  $$x^2 + \frac{b}{a}x + \frac{c}{a} = 0$$

**Q2.2: Transform $x^2 + \frac{b}{a}x$ into a perfect square $(x + k)^2$ by adding and subtracting a constant.**
- **Solution:** To make $x^2 + \frac{b}{a}x$ a perfect square, we take half of the coefficient of $x$ (which is $\frac{b}{2a}$) and square it ($\frac{b^2}{4a^2}$).
  $$x^2 + \frac{b}{a}x + \frac{b^2}{4a^2} - \frac{b^2}{4a^2} + \frac{c}{a} = 0$$
  $$\left(x + \frac{b}{2a}\right)^2 - \frac{b^2}{4a^2} + \frac{c}{a} = 0$$

**Q2.3: Solve for $x$ to find the "Quadratic Formula".**
- **Solution:**
  $$\left(x + \frac{b}{2a}\right)^2 = \frac{b^2}{4a^2} - \frac{c}{a}$$
  $$\left(x + \frac{b}{2a}\right)^2 = \frac{b^2 - 4ac}{4a^2}$$
  Taking the square root of both sides:
  $$x + \frac{b}{2a} = \pm \sqrt{\frac{b^2 - 4ac}{4a^2}}$$
  $$x = -\frac{b}{2a} \pm \frac{\sqrt{b^2 - 4ac}}{2a}$$
  $$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

---

## Question 3: The Discriminant ($D = b^2 - 4ac$)

**Q3.1: What happens to the roots if $D > 0$?**
- **Solution:** When $D > 0$, the term $\sqrt{D}$ is a positive real number. The equation yields two distinct real roots:
  $$x_1 = \frac{-b + \sqrt{D}}{2a}, \quad x_2 = \frac{-b - \sqrt{D}}{2a}$$

**Q3.2: What if $D = 0$?**
- **Solution:** When $D = 0$, the term $\sqrt{D}$ becomes $0$. Both roots converge to:
  $$x = -\frac{b}{2a}$$
  In this case, the roots are **real and equal**.

**Q3.3: What if $D < 0$?**
- **Solution:** When $D < 0$, $\sqrt{D}$ involves the square root of a negative number, resulting in imaginary components. The roots are **complex conjugates**:
  $$x = \frac{-b \pm i\sqrt{|D|}}{2a}$$

---

## Question 4: Relations between Roots and Coefficients

Let the roots be $\alpha = \frac{-b + \sqrt{D}}{2a}$ and $\beta = \frac{-b - \sqrt{D}}{2a}$.

**Q4.1: Use the quadratic formula to find $(\alpha + \beta)$.**
- **Solution:**
  $$\alpha + \beta = \frac{-b + \sqrt{D}}{2a} + \frac{-b - \sqrt{D}}{2a} = \frac{-2b}{2a} = -\frac{b}{a}$$

**Q4.2: Use it to find $(\alpha \cdot \beta)$.**
- **Solution:**
  $$\alpha \cdot \beta = \left(\frac{-b + \sqrt{D}}{2a}\right) \left(\frac{-b - \sqrt{D}}{2a}\right) = \frac{(-b)^2 - (\sqrt{D})^2}{4a^2}$$
  $$\alpha \cdot \beta = \frac{b^2 - (b^2 - 4ac)}{4a^2} = \frac{4ac}{4a^2} = \frac{c}{a}$$

**Q4.3: If you know the sum ($S$) and product ($P$) of roots, can you reconstruct the equation?**
- **Solution:** Yes. A quadratic equation with roots $\alpha$ and $\beta$ can be expressed as:
  $$(x - \alpha)(x - \beta) = 0$$
  $$x^2 - (\alpha + \beta)x + \alpha\beta = 0$$
  $$x^2 - Sx + P = 0$$
