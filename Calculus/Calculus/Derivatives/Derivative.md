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
## Notation
> There are many ways to show a **Derivative**
### Newtons Notation (Dot)
> The dot notation is simply **the BEST**: Shown with [[#Leibniz Notation]], $y=f(x),\frac{dy}{dx}= \dot{y}$ 
#### Newtons Higher Order
> Obviously, [[Higher Order Derivatives#Higher Order Derivatives|Higher Order Derivatives]] can be shown with **multiple dots**
> $\ddot{x}=\frac{d\dot{x}}{dt}$  
#### Example
> Used in **State Space Representation**
> $$\begin{align}
\dot{x}&=Ax+Bu\\
y&=Cx+Du
\end{align}$$
### Lagrange Notation
> This is the **f'(x) notation**. Or, explained with [[#Leibniz Notation]], $\frac{df}{dx}f(x)=f'(x)$ 

#### Lagrange Higher Order
> [[Higher Order Derivatives#Higher Order Derivatives|Higher Order Derivatives]] can be shown with **multiple primes**.
> $$f''(x)=f'(x)'$$
### Leibniz Notation
> This is the $\frac{df}{dx}f(x)$ notation.
> The $d$ **encodes** the [[#Definition Of the Derivative|Underlying Limit]] and resolves to $\lim_{\Delta x\to{0}} \frac{\Delta f(x)}{\Delta x}$ 

#### Leibniz Higher Order
> [[Higher Order Derivatives#Higher Order Derivatives|Higher Order Derivatives]] are weird
> $$f''(x)=\frac{d}{dx} \frac{d}{dx}f=\frac{d^{2}f}{dx^{2}}$$

#### Example
>$$\frac{df}{dx}(x^{2})=2x$$
>**Note the brackets otherwise it would be $(\frac{df}{dx}x)^{2}=1^{2}=1$**

#### With Known Value
> $$\left.\frac{dy}{dx}\right|_{x=1}$$