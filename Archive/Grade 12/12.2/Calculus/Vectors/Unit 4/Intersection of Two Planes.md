#vectors 
#calculus-unit-4 
# Intersection of Two Planes
---
![[Intersection of Two Planes 2022-03-31 14.13.41.excalidraw]]
> [[Augmented Matrix#Augmented Matrix|Augmented Matrix]] **Not required**
> $$\begin{align}
2x+3y+4z&=10\\
3x+y-z&=2\\
\left[\begin{array}{ccc|c}
2&3&4&10\\
3&1&-1&2\\
0&0&0&0
\end{array}\right]=
\left[\begin{array}{ccc|c}
2&3&4&10\\
0&-7&-14&-26\\
0&0&0&0
\end{array}\right]
\\
&-7y-14z=-26\\
&7y=26-14z\\
&y=\frac{26}{7}-2z\\
&2x+3y+4z=10\\
&2x+ \frac{3\cdot26}{7}-2z=10\\
&x=\frac{-4}{7}+z\\
&\vec{r}=(0,\frac{26}{7},-\frac{4}{7})+t(1,-2,1)
\end{align}$$
## Angle Between Planes
$$\cos{\theta}=\frac{\vec{n_1}\cdot\vec{n_2}}{|\vec{n_1}||\vec{n_{2}}|}
$$