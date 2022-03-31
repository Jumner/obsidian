#calculus-unit-4 
#vectors 
# Augmented Matrix
---
$$\begin{align}
\left[ {\begin{array}{cccc}
1&2&3\\
4&5&6
\end{array}}\right]
\end{align}$$
> Used to solve a **System of Equations**
> Because solving systems [[Intersection of a Line and a Plane|Algebraically]] is super impractical

## Problem
$$\begin{align}
x+2y-4z&=-7\\
2x+5y-z&=9\\
3x-y+2z&=7\\
\\
-2x-4y+8z&=14\\
2x+5y-z&=9\\
y+7z&=23\\
\\
-3x-6y+12z&=21\\
3x-y+2z&=7\\
-7y+14z&=-28\\
\\
-y+2z&=4\\
y+7z&=23\\
9z&=27\\
z&=3\\
\vdots
\\\text{It gets looong}
\end{align}$$
## A <u>Better</u> Way
$$\begin{align}
3x+4y+9z=7\\\\
\left[ {\begin{array}{cccc}
3&4&9\\
-1&4&-\frac{1}{2}\\
7&2&25
\end{array}}\right]
=\left[{\begin{array}{a}
11\\
-7\\
-1
\end{array}}\right]
\end{align}$$
Coefficient Matrix <- Constant Matrix -> 
### Gaussian Elimination
$$\begin{align}
\left[\begin{array}{ccc|c}
1&2&-4&-7\\
2&5&-1&9\\
3&-1&2&7
\end{array}\right]\tag{Augmented Matrix}
\\\vdots\\
\left[\begin{array}{ccc|c}
1&2&-4&-7\\
0_{1}&1&7&23\\
0_{2}&0_{3}&1&3
\end{array}\right]\tag{Echelon Form}
\end{align}$$
Steps: R1,R2-2R1,R3 ~ R1,R2,R3-3R1 ~ R1,R2,R3/7 ~ R1,R2,R3+R2 ~ R1,R2,R3/9
> You can always **move rows** up and down.
> You can multiply and divide rows. (Just like with the equation its based on)
> You simply multiply and add rows to create zeros
Then solve for z, plug and solve for y, plug and solve for x. Done!
![[Augmented Matrix 2022-03-30 14.23.47.excalidraw]]
$$
\begin{bmatrix}
1&2&3&10\\
4&5&6&11\\
7&8&9&12
\end{bmatrix}
$$