#vectors 
#calculus-unit-3 
# Distance From [[Points|Point]] To [[Equations of Lines|Line]]
---
> The shortest distance from a [[Points|Point]] to a [[Equations of Lines|Line]] is the **Perpendicular line** Between them
## Proof
1. The shortest distance from a **point** to a **line** is the $\perp$ distance
2. The shortest distance from a **point** to a **line** is **not** the $\perp$ distance
> Disprove Point 2 by **contradiction**

let A = a [[Points|Point]] **off** the **Line** $l$
let B = a [[Points|Point]] **on** the **Line** such that $\vec{AB}\perp l$
$\therefore \vec{AB}$ is **not the shortest** distance
let C = a [[Points|Point]] **on** the **Line** such that $\vec{AC}<\vec{AB}$ 
$\vec{AC}$ is the **Hypotenuse** of the ABC right triangle.
> $\therefore$ the shortest distance is the $\perp$ distance 

## In $\mathbb{R}^{2}$ Space
### Finding the Minimum Distance
let $p_{o}$ = known point on the line
let $d$ = minimum distance
let $p_{1}$ = known point off the line
$\vec{n}$ is the $\perp$ of the line
d is the [[Projection#Magnitude|Magnitude Projection]] of $p_{1}$ onto $\vec{n}$
$d= |proj(\vec{p_{1}} \text{ onto } \vec{n})|$
$d= \frac{|x_{1}A+y_{1}B+C|}{\sqrt{A^{2}+B^{2}}}$ 
## In $\mathbb{R}^3$ Space
> Because a [[Equations of Lines#Equations of Lines|Line]] does not have a **unique** normal vector, it is not as simple as [[#In mathbb R 2 Space|R2 Space]] 
### Finding the Minimum Distance
let $p_{1} = (x_{1},y_{1},z_{1})$
let $p_{0} = (x_{0}, y_{0}, z_{0})$
$\vec{m} =(a,b,c)$
let $\theta =$ angle between $\vec{p_{0}p_{1}}$ and $\vec{m}$
$\sin{\theta}= \frac{d}{|\vec{p_{0}p_{1}}|}$
$d= |\vec{p_{0}p_{1}}|\sin{\theta}\cdot \frac{|\vec{m}|}{|\vec{m}|}$ 
$d= \frac{|\vec{p_{0}p_{1}}||\vec{m}|\sin{\theta}}{|\vec{m}|}$ 
$d= \frac{|\vec{p_{0}p_{1}}\times\vec{m}|}{|\vec{m}|}$ 