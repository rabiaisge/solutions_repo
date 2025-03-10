# Problem 1
# Theoretical Foundation

## Deriving the Equations of Motion

Projectile motion is governed by Newton's Second Law:

\[ \mathbf{F} = m\mathbf{a} \]

For a projectile under the influence of gravity alone (neglecting air resistance), the only force acting is gravitational force:

\[ F_y = -mg \]

Thus, the equations of motion can be written as:

\[ m \frac{d^2 x}{dt^2} = 0 \quad \Rightarrow \quad \frac{d^2 x}{dt^2} = 0 \]

\[ m \frac{d^2 y}{dt^2} = -mg \quad \Rightarrow \quad \frac{d^2 y}{dt^2} = -g \]

### Solving for Position Functions

By integrating the acceleration equations:

1. **Horizontal Motion:**
   \[ \frac{dx}{dt} = v_0 \cos\theta \]
   \[ x(t) = v_0 \cos\theta \cdot t \]

2. **Vertical Motion:**
   \[ \frac{dy}{dt} = v_0 \sin\theta - g t \]
   \[ y(t) = v_0 \sin\theta \cdot t - \frac{1}{2} g t^2 \]

## Range of the Projectile

The range \( R \) is the horizontal distance when the projectile lands (\( y = 0 \)):

Setting \( y(t) = 0 \):

\[ 0 = v_0 \sin\theta \cdot t - \frac{1}{2} g t^2 \]

Solving for time \( t \):

\[ t = \frac{2 v_0 \sin\theta}{g} \]

Substituting this into \( x(t) \):

\[ R = v_0 \cos\theta \cdot \frac{2 v_0 \sin\theta}{g} \]

Using the identity \( 2 \sin\theta \cos\theta = \sin 2\theta \), we get:

\[ R = \frac{v_0^2 \sin 2\theta}{g} \]

## Effect of Initial Conditions

1. **Initial Velocity (\( v_0 \))**
   - The range increases quadratically with \( v_0 \):
   \[ R \propto v_0^2 \]

2. **Launch Angle (\( \theta \))**
   - The range is maximized when \( \theta = 45^\circ \), since \( \sin 2\theta \) reaches its peak at \( 90^\circ \).

3. **Gravitational Acceleration (\( g \))**
   - The range decreases with increasing \( g \):
   \[ R \propto \frac{1}{g} \]

This theoretical framework lays the foundation for further numerical simulations and experimental analysis.
