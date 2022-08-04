#vectors 
#calculus-unit-4 
# Intersection of Three [[Equations of Planes#Equations of Planes|Planes]]
---
![[Intersection of Three Planes 2022-04-01 13.34.09.excalidraw]]

| # Of Solutions | Description                        | Icon                                                             | Description of Solution                   | Normal Vectors Cmp                                |
| -------------- | ---------------------------------- | ---------------------------------------------------------------- | ----------------------------------------- | ------------------------------------------------- |
| 1              | 3 Planes intersect at a point      | ![[Intersection of Three Planes 2022-04-01 13.50.41.excalidraw]] | 1 Poi, One Solution                       | $\vec{n_1}\nparallel\vec{n_2}\nparallel\vec{n_3}$ |
| $\infty$       | 3 Planes intersect at a line       | ![[Intersection of Three Planes 2022-04-01 13.52.32.excalidraw]] | $\infty$ Solutions, line of intersection  | $\vec{n_1}\nparallel\vec{n_2}\nparallel\vec{n_3}$ |
| $\infty$       | 2 Planes Coincident, one intersect | ![[Intersection of Three Planes 2022-04-01 13.54.25.excalidraw]] | $\infty$ Solutions, line of intersection  | $\vec{n_1}\parallel\vec{n_2}\nparallel\vec{n_3}$  |
| $\infty$       | 3 Coincident                       |![[Intersection of Three Planes 2022-04-01 14.06.48.excalidraw]]                                                                  | $\infty$ Solutions, Plane of intersection | $\vec{n_1}\parallel\vec{n_2}\parallel\vec{n_3}$   |
| 0              | 3 parallel and distinct            |  ![[Intersection of Three Planes 2022-04-01 14.08.05.excalidraw]]                                                                |No Poi, No Solution                                           |$\vec{n_1}\parallel\vec{n_2}\parallel\vec{n_3}$                                                    |
| 0              | 3 Planes create a prism            |  ![[Intersection of Three Planes 2022-04-01 14.08.56.excalidraw]]                                                                |No Poi, No Solution. 3 Pairs of planes form 3 lines                                           |$\vec{n_1}\nparallel\vec{n_2}\nparallel\vec{n_3}$                                                   |
| 0              | 2 Coincident, one parallel         |   ![[Intersection of Three Planes 2022-04-01 14.09.46.excalidraw]]                                                               |No Poi, No Solution                                           |$\vec{n_1}\parallel\vec{n_2}\parallel\vec{n_3}$ 2 planes Coincident                                                   |
| 0              | 2 parallel, one intersect          |![[Intersection of Three Planes 2022-04-01 14.11.28.excalidraw]]                                                                  |No Poi, No Solution. 2 $\parallel$ planes intersect the third at 2 lines                                           |$\vec{n_1}\parallel\vec{n_2}\nparallel\vec{n_3}$                                                   |

> Solving it solves for points that are all **all 3 planes**. you can still have intersection of the planes that be a solution because its not on the third plane. 

## Solving The System
You plug into an [[Augmented Matrix#Augmented Matrix|Augmented Matrix]] and use [[Augmented Matrix#Gaussian Elimination|Gaussian Elimination]] to find a solution
### No Intersection
You can get something cursed like such
$$\left[\begin{array}{ccc|c}
\#&\#&\#&\#\\
0&0&\#&\#\\
0&0&0&\#
\end{array}\right]\therefore \#=0$$ 
### $\infty$ Solutions
#### Line
If you are left with 2 equations, you can sub to find a **Line of intersection**
$$
\left[\begin{array}{ccc|c}
1&1&2&-2\\
3&-1&14&6\\
1&2&0&-5
\end{array}\right]\sim
\left[\begin{array}{ccc|c}
1&1&2&-2\\
0&-4&8&0\\
0&1&-2&-3
\end{array}\right]\sim
\left[\begin{array}{ccc|c}
1&1&2&-2\\
0&-1&2&3\\
0&0&0&0
\end{array}\right]\therefore
\begin{align}

z&=z &z&=1-4t\\
y&=2z-3 &y&=2t-3 \\
x&=1-4z &z&=t
\end{align}
$$
#### Plane
If you are left with just 1 equation, you have a **Plane of Intersection**