# Ray Tracer 
## Created for CS4620, Spring 2024

# Terminology

## Vertex 
A position in space

## Dot product

The dot product of two vectors (a,b,c) and (d,e,f) is $a\cdot d+b\cdot e + c\cdot f$.

## Vector
A direction in space

What is the vector from (1,1) to (2,2)?



## Normalized Vector (Unit Vector)
A vector is length 1.
How? Divide all the components by the vector length.

Given vector (1,1,1), what is the normalized vector?

Given vector (3,0,-4), what is the normalized vector?

# Normal/Perpendicular/The Orthogonal Vector
v\cdot u=0 iff they are perpendicular, etc.

One way to do this is to take (a,b,c) and give (-b, a, 0). However, this will not work if both a and b are 0 (see the Fuzzy Ball Theorem). In that case, you can swizzle in another way, for example (0, -c, b).

Find a perdendicular vector to (-.5, -.5, 3)

Are vectors (2,3,4) and (0, -4, 3) perpendicular?

Are vectors (0,0,4) and (0,0,5) perpendicular?



# Ray
An infinite line that has an orgin, but no end.

$r_o+r_d*T$ or $r_x+r_dx*T+r_y+r_dy*T+r_z+r_dz*T$

Given a ray with origin (0,0,100) and a direction of (1,2,3), what is the position of the ray after T=3.2?



# Infinite Line
Ax+By+Cz+D=0
(A,B,C)\cdot (x,y,z)
D = -(A,B,C)\cdot (x,y,z)

Find the inifinite line that goes through theses two points:

(1,-2,-3), (-4, 5, 6)





# Infinite Plane
Ax+By+Cz+D=0

Find the infinite plane that lies along the triangle defined by the points:

(0,0,0), (1,0,0), (0,1,0)

