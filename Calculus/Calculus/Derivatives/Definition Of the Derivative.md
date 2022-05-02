#derivatives 
# Definition Of the Derivative
---
> To find the slope at a **point**. We find the slope between 2 points and look what happens when the distance **between** them goes to 0.

## Starting With Slope
> We start with the grade 9 equation of **Slope**
> $$\begin{align}
m=\frac{\text{rise}}{\text{run}}
\end{align}$$
We then create a **concrete value (h)** which is the distance between the 2 points
$$\begin{align}
m=\frac{f(x+h)-f(x)}{x+h-x}= \frac{f(x+h)-f(x)}{h}
\end{align}$$
This is the slope of the [[Tangent#Secant|Secant]]. To find the slope of the [[Tangent#Tangent|Tangent]], we must see what this approaches as $h\to0$
## Finding the Tangent
> Finding derivative of a simple function $f(x)=x^{2}$ requires a limit
> $$\begin{align}
\lim_{h\to{0}}&\frac{f(x+h)-f(x)}{h}\\
=\lim_{h\to{0}}&\frac{(x+h)^{2}-x^{2}}{h}\\
=\lim_{h\to{0}}&\frac{\cancel{x^2}+2x\cancel{h}+\cancelto{0}{h^{\cancel{2}}}-\cancel{x^{2}}}{\cancel{h}}=2x\\
\therefore& \frac{df}{dx}x^{2}=2x
\end{align}$$
Note that $h^{2}$ is divided by $h$ to become just $h$. Since $h\to0$, it becomes 0