#calculus 
#limits 
# Limits
---
> What happens to $f(x)$  as $x$ **approaches** a value
> $$\lim_{x\to0} f(x)$$

^a2e901

Start with a simple function $f(x)=x^{2} +2$ 
$f(1) = 3$, $P(1,3)$ $\text{Domain} = \{x \in \mathbb{R}\}$
$f(x)$ is continuous at $x=1$
Because this is impossible at **all** points in the domain, we find the points that **Are not Continuous**
Onto the [[#Limits|Limit]]
![[#^a2e901]]
When x **Approaches 1** $f(x)$ **Approaches 3**
$$\therefore \lim_{x\to1}f(x)=\lim_{x\to1}(x^{2}+2)$$
Parenthesis are required, $\lim_{x\to1}x^2+2=2+\lim_{x\to1}x^{2}$ 

## Limits with [[Graphing Split Functions#Removable Discontinuity|Removable Discontinuities]]
$$\begin{align}
f(x)&=\frac{(x+2)\cancel{(x-1)}}{\cancel{(x-1)}}\\
f(x)&=x+2, x\ne1,RD(1,3)\\
\lim_{x\to1}f(x)&=\lim_{x\to1}(x+2)=3
\end{align}$$
## Limits with [[Graphing Split Functions#Graphing Split Functions|Split Functions]]
$$
f(x)=\left\{\begin{align} x^{2}, x<1\\2,x\ge1\end{align}\right.
$$$$
\begin{align}
\lim_{x\to1}f(x)\text{ Does Not Exist (DNE)}
\end{align}
$$
There are 2 Options (1, and 2) so no concrete limit exists
## Condition To Exist
For a [[#Limits|Global Limit]] to exist, the [[#Left Hand Limit|Left]] and [[#Right Hand Limit|Right Hand Limits]] Must both **Exist** and **Be Equal**
$$\lim_{x\to a}f(x)=\lim_{x\to a^{-}}f(x)=\lim_{x\to a^{+}}f(x)=L, L\in\mathbb{R}$$
## Left and Right Hand Limit (RH, LH)
### Left Hand Limit
$$\lim_{x\to1^{-}}$$
> The Limit coming from the Left (Negative)
### Right Hand Limit
$$\lim_{x\to1^{+}}$$
> The Limit coming from the Right (Positive)

## Solving Algebraically
$$\lim_{x\to a}f(x)=f(a)$$
This **only** works when you **Don't get either**
1. $\frac{0}{0}$ Indeterminate
2. $\frac{\#}{0}$ Undefined