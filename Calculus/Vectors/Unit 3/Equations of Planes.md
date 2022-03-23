#calculus-unit-3 
#vectors 
# Equations of Planes
---
> A plane can be formed with 2 [[Equations of Lines#Direction Algebraic Vectors Algebraic Vectors Vectors|Direction Vectors]] and a [[Points|Point]]

these 2 direction vectors must be non parallel
$\vec{a}\nparallel\vec{b}$ 

if $p_{0}$ and $p$ are points on the plane, $p_{0}p$ is coplanar with $\vec{a}$ and $\vec{b}$ $\therefore \vec{P_{0}p}=s\vec{a}+t\vec{b}, s\in\mathbb{R}$ 
## Vector Equation
![[Vector Equations#Plane In mathbb R 3 Space]]
## Parametric Equations
![[Parametric Equations#Plane In mathbb R 3 Space]]
## Cartesian Equation
![[Cartesian Equations#Planes In mathbb R 3 Space]]
## With 3 Points
> A Plane can also be defined using 3 [[Points]]

1. Pick 2 [[Vectors#Vector|Vectors]]
$$\begin{align}
&A(1,0,-3), B(2,-3,1), C(3,5,-3)\\
&\vec{AB}=(1,-3,4), \vec{AC}=(2,5,0)\\
&\vec{r}=(3,5,3)+s(1,-3,4)+t(2,5,0), s,t\in\mathbb{R}
\end{align}$$

## Checking if [[Points|Point]] is on a Plane
1. Substitute the **Point** into the [[#Parametric Equation]] 
2. Clean up the numbers
3. Use **2** equations to solve for **s** and **t**
4. Test values with **Third**
> If this fails, the line is on on the plate

## With 2 Lines that are Parallel
---
The 2 direction vectors in the [[#Vector Equation]] **Must not** be parallel. Instead, Because lines cannot move, you can pick 3 points on the two lines and [[#With 3 Points|solve for a plane]].
