#derivatives 
# Chain Rule
---
> The [[#Chain Rule]] is a rule that determines the [[Derivative#Definition Of the Derivative|Derivative]] when **functions are combined**

## Addition
> It is fairly intuitive that the **derivative of the sum** is equal to the **sum of the derivatives**
> $$\begin{align}
\frac{df}{dx}2x^{2}+4x+4&=\\
\frac{df}{dx}2x^{2}+ \frac{df}{dx}4x + \frac{df}{dx}4&=\\
2x+4+0&=2x+4
\end{align}$$
## Multiplication
> Functions can be multiplied together. This one is slightly unintuitive. But if can be thought of as **Left d right, right d left**
## Function Composition
> Functions are **composed** when they are put inside each other.
> $$\begin{align}
f'(g(x))=f'(g(x))\cdot g'(x)
\end{align}$$
$$\begin{align}
f(x)&=\sin(x)\\
g(x)&=x^{2}\\
f(g(x))&=\sin(x^{2})\\
f'(x)=\cos(x)&, g'(x)=2x\\
\frac{df}{dx}f(g(x))&=\frac{df}{\cancel{dg}}f(g(x))\cdot \frac{\cancel{dg}}{dx}g(x)\\
&=f'(g(x))\cdot g'(x)\\
&=\cos(x^{2})\cdot 2x
\end{align}$$