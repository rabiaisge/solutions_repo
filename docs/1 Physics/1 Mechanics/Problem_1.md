# Problem 1

---
# Investigating the Range as a Function of the Angle of Projection

## 1. Theoretical Foundation

### 1.1 Governing Equations of Motion

Projectile motion is governed by Newton's Second Law of Motion, which states:

$$\mathbf{F}=m\mathbf{a}$$

For a projectile launched with an initial velocity $v_0$ at an angle $\theta$, we decompose the motion into horizontal and vertical components:

#### Horizontal Motion

$$x(t)=v_0\cos\theta\cdot t$$

Since there is no horizontal acceleration (assuming no air resistance), the horizontal velocity remains constant:

$$v_x=v_0\cos\theta$$

#### Vertical Motion

The vertical motion is influenced by gravity $g$, and follows the kinematic equations:

$$y(t)=v_0\sin\theta\cdot t-\frac{1}{2}gt^2$$

The vertical velocity is given by:

$$v_y=v_0\sin\theta-gt$$

At the peak of the trajectory, the vertical velocity becomes zero:

$$0=v_0\sin\theta-gt_{max}$$

Solving for $t_{max}$:

$$t_{max}=\frac{v_0\sin\theta}{g}$$

The total time of flight is twice this value:

$$T=\frac{2v_0\sin\theta}{g}$$

### 1.2 Derivation of the Range Equation

The range $R$ is the horizontal distance traveled when $y=0$. Using the horizontal motion equation:

$$R=v_xT$$

Substituting $v_x=v_0\cos\theta$ and $T=\frac{2v_0\sin\theta}{g}$:

$$R=v_0\cos\theta\cdot\frac{2v_0\sin\theta}{g}$$

Using the trigonometric identity $2\sin\theta\cos\theta=\sin2\theta$, we obtain:

$$R=\frac{v_0^2\sin2\theta}{g}$$

### 1.3 Influence of Initial Conditions

- **Initial Velocity ($v_0$)**: Increasing $v_0$ increases $R$ quadratically.
- **Angle of Projection ($\theta$)**: Maximum range occurs at $\theta=45^\circ$.
- **Gravitational Acceleration ($g$)**: A higher $g$ decreases the range.
- **Launch Height ($h$)**: If launched from a height $h$, the total flight time increases, affecting $R$.

#### Modified Range Equation for Nonzero Initial Height

If the projectile is launched from height $h$, the quadratic equation for time of flight is:

$$y=v_0\sin\theta\cdot t-\frac{1}{2}gt^2+h=0$$

Solving for $t$, we get:

$$t=\frac{v_0\sin\theta+\sqrt{(v_0\sin\theta)^2+2gh}}{g}$$

The range then becomes:

$$R=v_0\cos\theta\cdot\left(\frac{v_0\sin\theta+\sqrt{(v_0\sin\theta)^2+2gh}}{g}\right)$$

This equation accounts for different launch heights, making it more general.

---

## 2. Analysis of the Range

### 2.1 Dependence on the Angle of Projection

The horizontal range $R$ depends on the angle of projection $\theta$ as:

$$R=\frac{v_0^2\sin2\theta}{g}$$

This function is symmetric about $45^\circ$, meaning that complementary angles ($\theta$ and $90^\circ - \theta$) result in the same range. The maximum range occurs when:

$$\theta=45^\circ$$

At this angle, the sine function reaches its maximum value of 1, giving:

$$R_{max}=\frac{v_0^2}{g}$$

### 2.2 Influence of Initial Velocity

From the range equation:

$$R \propto v_0^2$$

This quadratic relationship implies that doubling the initial velocity results in a fourfold increase in range.

### 2.3 Influence of Gravitational Acceleration

Since:

$$R \propto \frac{1}{g}$$

A higher gravitational acceleration reduces the range, which explains why projectiles on the Moon (where $g$ is lower) travel much farther than on Earth.

---

