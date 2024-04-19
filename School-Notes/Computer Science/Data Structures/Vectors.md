Uses of vectors:
- Graphics and 3D graphics - Images are defined as paths, not distinct bit patterns, rules of mathematics allow scaling without distortion.
- Computer games / simulations - The combination of moving forces, represented by vectors, can be resolved into a single path by using the same mathematical rules. For example, a ship steering against the wind and sea, calculating collision paths.
- Multiple dimensions - Can represent 2, 3, or more dimensions.

In order to translate from mathematical notation to a notation more useful in programming, we use a function map The notation 'S maps to $\mathbb{R}$' means a vector can be used as a location indicator, where S = {0, 1, 2, 3} maps to [2.55, -3.88, 4.11, 5.77]

The convex combination of two vectors is the space bounded by the vectors u, v, and a line connecting the tips. It is an expression in the form:
$$w = \alpha u + \beta v$$

## Dot Product
A method for multiplying 2 vectors together written by a dot $(u \cdot v)$. The result multiplies corresponding components of each vector.
$$u \cdot v = u_{1}v_{1} + u_{2}v_{2} + u_{3}v_{3} + \ldots u_{n}v_{n}$$

## Angle
The length of the vectors can be written in mathatical notation as $\|u\|$ and $\|v\|$.
The angle can be calculated by:
$$\cos{\theta} = \frac{u \cdot v}{\|u\| \cdot \|v\|}$$