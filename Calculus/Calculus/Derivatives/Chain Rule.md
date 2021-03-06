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
> The 3b1b way to think about this is a rectangle

### Example
![[Chain Rule 2022-05-04 13.32.06.excalidraw]]
### Extended With Many Terms
What if you want to multiply more than 2 functions?
You can think of **a cube**, you can think of **chained** multiplication of **2 terms**, or you can think of what it means.
> You get it from the value (think of it list **state** or position) of each term and one of the derivatives. You think of how much does this term impact the derivative. In other words, the impact of a term is determined by the value of the other terms.
> The end result is that $h(x)=f(x)g(x)p(x), h'(x)=f'(x)g(x)p(x) +f(x)g'(x)p(x) +f(x)g(x)p'(x)$
### Function Exponents
> $\frac{df}{dx}(f(x)^{n})=n \cdot f'(x)\cdot f(x)^{n-1}$
> For each multiplication you get one term that includes $f'(x)$ multiplied by $f(x)$ $n-1$ times. Of these multiplicative terms, you have n of them. 
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
### But Why?
When we look at the derivative of an outside function ($\sin(x)$) we are asking how $\sin(x)$ changes relative to a **change in x** so if we want to find the derivative of $\sin{\sin{x}}$ we must first find how much $\sin{\sin{x}}$ changes relative to a change in $\sin{x}$. To get the change **relative to $x$**, we must multiply by how $\sin{x}$ is changing relative to $x$. In math terms, it looks like this:
$$\begin{align}
&\frac{d}{d\sin{x}}\sin\sin{x}=\cos{\sin{x}},\frac{d\sin{x}}{dx}=\cos{x},\\
&\therefore \frac{d}{dx}\sin\sin{x}= \frac{d}{\cancel{d\sin{x}}}\sin\sin{x}\cdot \frac{\cancel{d\sin{x}}}{dx}=\cos\sin{x}\cdot\cos{x}
\end{align}$$
You definitely feel like you're missing information but you're not.
> Put one more simple way
> $$\begin{align}
y&=f(u), u=g(x), y=f(g(x))\\
\frac{dy}{dx}&=\frac{dy}{\cancel{du}}\cdot \frac{\cancel{du}}{dx}=f'(g(x))\cdot g'(x)
\end{align}$$