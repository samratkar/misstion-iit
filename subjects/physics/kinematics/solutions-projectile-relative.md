# Solutions: 2D Motion (Projectile & Relative)

This document provides detailed solutions and explanations for the questions posed in the Projectile and Relative Motion QBP.

---

### Question 1: Independence of Horizontal and Vertical Motion

**Q1.1: Which ball hits the ground first?**
**Solution:** Both balls hit the ground at the same time.
**Explanation:** Vertical motion is independent of horizontal motion. For both balls, the initial vertical velocity $u_y = 0$ and the vertical acceleration is $a_y = g$. Using the kinematic equation $s = ut + \frac{1}{2}at^2$:
$$H = 0 + \frac{1}{2}gt^2 \implies t = \sqrt{\frac{2H}{g}}$$
Since $H$ and $g$ are the same for both, the time of flight $t$ is identical.

**Q1.2: What is the horizontal distance (range) covered by the first ball when it hits the ground?**
**Solution:** $R = u\sqrt{\frac{2H}{g}}$
**Explanation:** Horizontal motion has zero acceleration ($a_x = 0$). The distance is:
$$x = u_x \cdot t$$
Substituting $u_x = u$ and $t = \sqrt{\frac{2H}{g}}$ from Q1.1:
$$R = u\sqrt{\frac{2H}{g}}$$

**Q1.3: Does the horizontal velocity change during the flight? Why?**
**Solution:** No, the horizontal velocity remains constant ($u$).
**Explanation:** In the absence of air resistance, there are no horizontal forces acting on the ball ($F_x = 0$). According to Newton's Second Law ($F = ma$), the horizontal acceleration $a_x = 0$, thus velocity remains unchanged.

---

### Question 2: The Projectile Trajectory

**Q2.1: Express the horizontal and vertical components of velocity at any time $t$.**
**Solution:**
- Horizontal: $v_x = u \cos \theta$
- Vertical: $v_y = u \sin \theta - gt$
**Explanation:**
The initial velocity components are $u_x = u \cos \theta$ and $u_y = u \sin \theta$.
With $a_x = 0$, $v_x = u_x = u \cos \theta$.
With $a_y = -g$, $v_y = u_y + a_y t = u \sin \theta - gt$.

**Q2.2: Derive the expression for Time of Flight ($T$) and Maximum Height ($H_{max}$).**
**Solution:**
- $T = \frac{2u \sin \theta}{g}$
- $H_{max} = \frac{u^2 \sin^2 \theta}{2g}$
**Explanation:**
1. **Time of Flight:** The projectile returns to the same vertical level ($y = 0$).
   $$y = u_y T - \frac{1}{2}g T^2 = 0 \implies (u \sin \theta)T = \frac{1}{2}g T^2$$
   Solving for $T$ (ignoring $T=0$): $T = \frac{2u \sin \theta}{g}$.
2. **Maximum Height:** At peak height, vertical velocity $v_y = 0$.
   $$v_y^2 = u_y^2 - 2g H_{max} \implies 0 = (u \sin \theta)^2 - 2g H_{max}$$
   $H_{max} = \frac{u^2 \sin^2 \theta}{2g}$.

**Q2.3: Show that for a fixed $u$, the range is same for angles $\theta$ and $(90^\circ - \theta)$.**
**Solution:**
The range formula is $R = \frac{u^2 \sin 2\theta}{g}$.
For angle $\alpha = 90^\circ - \theta$:
$$R' = \frac{u^2 \sin(2(90^\circ - \theta))}{g} = \frac{u^2 \sin(180^\circ - 2\theta)}{g}$$
Using the identity $\sin(180^\circ - A) = \sin A$:
$$R' = \frac{u^2 \sin 2\theta}{g} = R$$
Thus, complementary angles yield the same range.

---

### Question 3: Relative Motion in 2D (Rain-Man Problems)

**Q3.1: What is the velocity of rain *relative to the man* ($\vec{v}_{RM}$)?**
**Solution:** $\vec{v}_{RM} = -4\hat{i} - 3\hat{j} \text{ km/h}$, Magnitude $= 5 \text{ km/h}$.
**Explanation:**
Let $\hat{i}$ be horizontal and $\hat{j}$ be vertical (upward).
$\vec{v}_R = -3\hat{j}$
$\vec{v}_M = 4\hat{i}$
$\vec{v}_{RM} = \vec{v}_R - \vec{v}_M = -3\hat{j} - 4\hat{i} = -4\hat{i} - 3\hat{j}$.
Magnitude $|\vec{v}_{RM}| = \sqrt{(-4)^2 + (-3)^2} = 5 \text{ km/h}$.

**Q3.2: At what angle should the man hold his umbrella to stay dry?**
**Solution:** $\theta = \tan^{-1}(4/3)$ from the vertical (tilted forward).
**Explanation:**
The umbrella must be held in the direction opposite to $\vec{v}_{RM}$ (i.e., in the direction of velocity of rain relative to man).
The angle $\theta$ with the vertical is given by:
$$\tan \theta = \frac{|v_{RM, x}|}{|v_{RM, y}|} = \frac{4}{3}$$
$\theta = \tan^{-1}(1.33) \approx 53.1^\circ$.

**Q3.3: If the man starts running faster, does the angle of the umbrella increase or decrease?**
**Solution:** Increase.
**Explanation:** $\tan \theta = \frac{v_M}{v_R}$. If $v_M$ increases while $v_R$ is constant, $\tan \theta$ increases, and thus $\theta$ increases. The man must tilt the umbrella more forward.

---

### Question 4: River-Boat Problems

**Q4.1: To cross the river in the "shortest time", in which direction should the boat point?**
**Solution:** Directly perpendicular to the river bank.
**Explanation:** The time taken to cross is $t = \frac{d}{v_{br} \cos \alpha}$, where $\alpha$ is the angle with the perpendicular. $t$ is minimized when $\cos \alpha = 1$, which means $\alpha = 0^\circ$.

**Q4.2: To cross the river via the "shortest path" (straight across), what condition must be met by $v_{br}$ and $v_r$?**
**Solution:** $v_{br} \ge v_r$.
**Explanation:** For the shortest path (resultant velocity along the perpendicular), the boat must point upstream at an angle $\theta$ such that $v_{br} \sin \theta = v_r$.
$$\sin \theta = \frac{v_r}{v_{br}}$$
Since $|\sin \theta| \le 1$, we must have $v_r \le v_{br}$.

**Q4.3: Calculate the "drift" if the boat points perpendicular to the current.**
**Solution:** $Drift = \frac{v_r \cdot d}{v_{br}}$
**Explanation:**
Time to cross $t = \frac{d}{v_{br}}$.
Horizontal displacement (drift) is caused by the river velocity $v_r$:
$$Drift = v_r \cdot t = v_r \cdot \left(\frac{d}{v_{br}}\right) = \frac{v_r d}{v_{br}}$$
