#calculus-unit-4
#vectors 
# Intersection of Two Lines
---
## Intersection of 2 [[Equations of Lines#Equations of Lines|Lines]] in $\mathbb{R}^{2}$ Space
![[Intersection of Two Lines 2022-03-28 13.48.35.excalidraw]]
## Intersection of 2 [[Equations of Lines#Equations of Lines|Lines]] in $\mathbb{R}^{3}$ Space
![[Intersection of Two Lines 2022-03-28r3.excalidraw]]

## Distance between 2 Skew [[Equations of Lines#Equations of Lines|Lines]]
Consider 2 Skew Lines
> You can simply [[Projection#Scaler Projection|Project]] the line ($\vec{PQ}$) onto the [[Cross Product#Cross Product|Cross Product]] of the 2 **Direction Vectors**
$$\begin{align}
&\vec{r_{1}}=\vec{OP}+t\vec{m_1}\\
&\vec{r_2}=\vec{OQ}+s\vec{m_2}\\
&d= \frac{|\vec{PQ}\cdot\vec{m_{1}}\times\vec{m_2}|}{|\vec{m_{1}}\times\vec{m_2}|}
\end{align}$$
![[Intersection of Two Lines 2022-03-29 13.38.05.excalidraw]]

---

## Solving The System
Substitute the [[Parametric Equations#Parametric Equations|Parametric Equations]] into the [[Symmetric Equations#Symmetric Equations|Symmetric Equations]] and solve for **t**. The parameter [[#Intersection of 2 Equations of Lines Equations of Lines Lines in mathbb R 2 Space|Noted Above]] 
### Examples
$$\begin{align}
&\vec{r_{1}} = (-1,1,0) + t(3,4,-2), t\in\mathbb{R}\\
&\vec{r_2}=(-1,0,-7) + s(2,3,1), t\in\mathbb{R}\\
&\vec{m_{1}}=(3,4,-2), \vec{m_{2}}=(2,3,1)\\
&\therefore \vec{m_1}\nparallel\vec{m_{2}}\\
&\therefore \vec{r_{1}}\nparallel \vec{r_{2}}\\
&\text{Param eqs of } r_{1}:\\
&x=-1+3t\\
&y=1+4t\\
&z=-2t\\
&\text{Symm eqs of }r_{2}:\\
& \frac{x+1}{2} = \frac{y}{3} = z+7\\
& \frac{\cancel{-1}+3t+\cancel1}{2} = \frac{1+4t}{3} = -2t+7 \\
&\frac{3t}{2}= \frac{1+4t}{3}\\
&t=2\\
& \frac{1+3t}{3} = -2t+7\\
&t=2\\
&\therefore \text{The 2 lines intersect at the unique point }(5,9,-4)
\end{align}$$
make sure you sub into the right eq.
> If you solve for **t**, **DO NOT** sub into the equation with **s**
$$\begin{align}
\frac{-3+2t+7}{-2}&=4-t-1 &x&=3\\
\frac{2t+4}{-2}&=-t+3&y&=3+4
\end{align}$$