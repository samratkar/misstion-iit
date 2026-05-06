# Solution Key: Motion in a Straight Line (1D Kinematics)

This document provides detailed step-by-step solutions for the question-based pedagogy module located at `subjects/physics/kinematics/qbp-1d-motion.md`.

---

# Phase 1: Foundation

### Group 1.1: The Geometry of Motion
- **S1.1:** Displacement ($\Delta x$) is the change in position.
  $$\Delta x = x_f - x_i = 5\text{m} - (-2\text{m}) = +7\text{m}$$
- **S1.2:** 
  - **Distance:** Path 1 ($x=-2$ to $5$) is $7\text{m}$. Path 2 ($x=5$ to $0$) is $5\text{m}$. Total distance = $7 + 5 = 12\text{m}$.
  - **Net Displacement:** $x_f = 0$, $x_i = -2$. $\Delta x = 0 - (-2) = +2\text{m}$.
- **S1.3:** 
  - **Distance:** $1.5 \times \text{circumference} = 1.5 \times 2\pi R = 3\pi R$.
  - **Displacement:** After $1.5$ revolutions, the particle is at the diametrically opposite point. The straight-line distance is the diameter $= 2R$.
- **S1.4:** When the particle moves in a **single direction** along a straight line without reversing.
- **S1.5:** **No.** Distance is the actual path length, while displacement is the shortest straight-line distance between start and end. Mathematically, $\text{Distance} \ge |\text{Displacement}|$.

### Group 1.2: Rate of Change - Average Values
- **S1.6:** **No.** Average speed is total distance divided by total time. Arithmetic mean only works for equal time intervals.
- **S1.7:** Let half distance be $d$. Time $t_1 = d/v_1$, $t_2 = d/v_2$.
  $$v_{avg} = \frac{2d}{\frac{d}{v_1} + \frac{d}{v_2}} = \frac{2v_1v_2}{v_1 + v_2} \text{ (Harmonic Mean)}$$
- **S1.8:** Let half time be $T/2$. Distance $d_1 = v_1(T/2)$, $d_2 = v_2(T/2)$.
  $$v_{avg} = \frac{v_1(T/2) + v_2(T/2)}{T} = \frac{v_1 + v_2}{2} \text{ (Arithmetic Mean)}$$
- **S1.9:** For a round trip, net displacement is $0$. Therefore, **Average Velocity = 0**.
- **S1.10:** If a particle returns to its starting point, its displacement is zero (avg. velocity $= 0$), but it has traversed a non-zero path length (avg. speed $> 0$).

### Group 1.3: Transition to Instantaneous Motion
- **S1.11:** It becomes the **instantaneous velocity** ($v = \frac{dx}{dt}$).
- **S1.12:** It represents **instantaneous speed**.
- **S1.13:** $v(t) = \frac{d}{dt}(4t^2 + 2t) = 8t + 2$.
  At $t=2\text{s}$, $v = 8(2) + 2 = 18\text{ m/s}$.
- **S1.14:** If velocity is constant, the instantaneous velocity at any point is **equal** to the average velocity over any interval.
- **S1.15:** Acceleration is the rate of change of velocity: $a = \frac{dv}{dt} = \frac{d^2x}{dt^2}$.

---

# Phase 2: Concept Building

### Group 2.1: The Kinematic Equations
- **S2.1:** $\int_u^v dv = \int_0^T a \, dt \implies v - u = aT \implies v = u + aT$.
- **S2.2:** $\frac{dx}{dt} = u + at \implies \int_0^s dx = \int_0^t (u + at) dt \implies s = ut + \frac{1}{2}at^2$.
- **S2.3:** $a = v \frac{dv}{dx} \implies \int_u^v v \, dv = \int_0^s a \, dx \implies \frac{v^2 - u^2}{2} = as \implies v^2 = u^2 + 2as$.
- **S2.4:** $u = 20, v = 0, t = 5$.
  - $a = \frac{v-u}{t} = \frac{0-20}{5} = -4\text{ m/s}^2$.
  - $s = ut + \frac{1}{2}at^2 = 20(5) + \frac{1}{2}(-4)(25) = 100 - 50 = 50\text{m}$.
- **S2.5:** $s_n = s(n) - s(n-1) = [un + \frac{1}{2}an^2] - [u(n-1) + \frac{1}{2}a(n-1)^2]$
  $$s_n = u + \frac{a}{2}[n^2 - (n^2 - 2n + 1)] = u + \frac{a}{2}(2n - 1)$$

### Group 2.2: Mastery of Constant Acceleration
- **S2.6:** Using $s_n \propto (2n-1)$ for $u=0$:
  Ratio $= (2(1)-1) : (2(2)-1) : (2(3)-1) = 1 : 3 : 5$.
- **S2.7:** Velocity after 1 plank $v = \frac{19}{20}u$.
  $v^2 = u^2 + 2as \implies (\frac{19}{20}u)^2 = u^2 + 2as \implies 2as = -\frac{39}{400}u^2$.
  To stop ($V=0$): $0 = u^2 + N(2as) = u^2 - N(\frac{39}{400}u^2) \implies N = \frac{400}{39} \approx 10.25$.
  Minimum **11 planks** are required.
- **S2.8:** Let length be $L$. $v^2 = u^2 + 2aL$.
  Middle point distance is $L/2$. $v_{mid}^2 = u^2 + 2a(L/2) = u^2 + aL$.
  Substituting $aL = \frac{v^2 - u^2}{2}$, we get $v_{mid} = \sqrt{\frac{u^2 + v^2}{2}}$.
- **S2.9:** Acceleration is **zero** (velocity is constant).
- **S2.10:** Since the distance in successive seconds increases by a constant amount ($2\text{m}$), acceleration is **constant**. ($s_n - s_{n-1} = a = 2\text{ m/s}^2$).

### Group 2.3: Motion Under Gravity
- **S2.11:** At the peak, velocity is **zero**, and acceleration is **$g$ (downwards)**.
- **S2.12:** $v = u - gt \implies 0 = u - gt \implies t = u/g$.
  $0^2 = u^2 - 2gH \implies H = u^2/2g$.
- **S2.13:** $t_{asc} = u/g$. From $H$, $s = \frac{1}{2}gt^2 \implies H = \frac{1}{2}gt_{desc}^2 \implies t_{desc} = \sqrt{2H/g} = u/g$.
- **S2.14:** They are **identical** ($g \approx 9.8\text{ m/s}^2$ downwards).
- **S2.15:** **Increase.** The velocity of lower drops is higher than the drops above them at any instant, so they cover more distance in the same time interval. $\Delta y = gtT - \frac{1}{2}gt^2$.

### Group 2.4: The Language of Graphs
- **S2.16:** Acceleration is **zero**.
- **S2.17:** Integrate the absolute value of velocity: $\int |v| \, dt$ (Sum of magnitudes of areas).
- **S2.18:** Sign is **positive** (curvature is upwards).
- **S2.19:** **Instantaneous acceleration**.
- **S2.20:** $a = -g$ (horizontal line below axis). At collision, a sudden vertical spike (positive) represents the elastic bounce, then returns to $-g$.

---

# Phase 3: Advanced Application

### Group 3.1: Calculus-Based Kinematics
- **S3.1:** $v = \int a \, dt = \int (3t^2 + 2t) dt = t^3 + t^2 + C$. Since $v(0)=0$, $C=0$. $v(t) = t^3 + t^2$.
- **S3.2:** $a = v \frac{dv}{dx} = (k \sqrt{x}) \cdot \frac{d}{dx}(k \sqrt{x}) = k\sqrt{x} \cdot \frac{k}{2\sqrt{x}} = \frac{k^2}{2}$.
- **S3.3:** $v \frac{dv}{dx} = -kv^2 \implies \frac{dv}{v} = -k dx \implies \ln(\frac{v}{v_0}) = -kx \implies v(x) = v_0 e^{-kx}$.
- **S3.4:** $v = A\omega \cos(\omega t)$, $a = -A\omega^2 \sin(\omega t) = -\omega^2 x$. Max acceleration at **extremities** ($x = \pm A$).
- **S3.5:** $\sqrt{x} = t - 3 \implies x = (t-3)^2$. $v = \frac{dx}{dt} = 2(t-3)$.
  When $x=0, t=3$. Thus, $v(3) = 2(3-3) = 0\text{ m/s}$.

### Group 3.2: Relative Motion in 1D
- **S3.6:** $v_{AB} = v_A - v_B$.
- **S3.7:** Relative speed $= 10 - (-15) = 25\text{ m/s}$. Total length $= 200\text{m}$.
  Time $= 200/25 = 8\text{s}$.
- **S3.8:** Relative acceleration $a_{rel} = (-g) - (-g) = 0$.
- **S3.9:** Relative velocity is constant: $v_{rel} = u$. Distance $H$. Time $t = H/u$.
- **S3.10:** Time for trains to collide $t = 40/(10+10) = 2\text{ hours}$.
  Bird distance $= \text{speed} \times t = 20 \times 2 = 40\text{km}$.

### Group 3.3: Stopping Distance and Reaction Time
- **S3.11:** It is the time elapsed between seeing an obstacle and applying brakes. The car covers distance at constant speed during this time.
- **S3.12:** Distance $= u t_r$.
- **S3.13:** $d_s = u t_r + \frac{u^2}{2a}$.
- **S3.14:** Braking distance $\propto u^2$. Doubling speed increases it by factor of **4**.
- **S3.15:** $u = 30, t_r = 0.2, a = 5$.
  $d_{total} = (30 \times 0.2) + \frac{30^2}{2 \times 5} = 6 + 90 = 96\text{m}$.
  Since $96\text{m} < 100\text{m}$, **he can stop in time**.
