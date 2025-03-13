# Problem 1
# Orbital Period and Orbital Radius

## Theoretical Foundation

Kepler's Third Law states that the square of a planet's orbital period is proportional to the cube of its orbital radius. This law can be derived using Newton's laws of motion and universal gravitation.

### Derivation of Keplers Third Law

For a planet orbiting a star in a circular orbit, the gravitational force provides the necessary centripetal force:

$$\frac{GMm}{r^2}=m\frac{v^2}{r}$$

where:
- $G$ is the gravitational constant,
- $M$ is the mass of the central star,
- $m$ is the mass of the orbiting body,
- $r$ is the orbital radius,
- $v$ is the orbital velocity.

Since the orbital period $T$ is related to velocity by:

$$v=\frac{2\pi r}{T}$$

Substituting this into the centripetal force equation:

$$\frac{GM}{r^2}=\frac{(2\pi r)^2}{T^2r}$$

Rearranging:

$$T^2=\frac{4\pi^2}{GM}r^3$$

which confirms Kepler’s Third Law:

$$T^2\propto r^3$$

### Implications in Astronomy

- This relationship allows for the determination of planetary masses and distances.
- It is essential for calculating satellite orbits.
- It applies to a wide range of celestial systems, from planets to exoplanets and binary stars.

## Real-World Examples

- **The Moon’s orbit around Earth**: Using Kepler’s Law, one can verify its orbital period.
- **Planets in the Solar System**: The law holds for all planets orbiting the Sun.
- **Artificial Satellites**: Engineers use this law to design satellite trajectories.

## Implementation

1. **Develop a computational model** to simulate circular orbits.
2. **Verify Kepler’s Third Law** numerically by computing $T^2$ and $r^3$.
3. **Visualize orbits** with plots of motion over time.

## Deliverables

- A Markdown document with Python code for simulations.
- Graphical representations of orbital paths.
- Verification of Kepler’s Third Law through numerical analysis.
- Discussion on extensions to elliptical orbits.

This study provides a rigorous yet accessible approach to understanding orbital mechanics and celestial dynamics.
