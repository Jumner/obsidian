#calculus 
#limits 
# Limits
---
> What happens to $f(x)$  as $x$ **approaches** a value
> $$\lim_{x\to0} f(x)$$

^a2e901

Start with a simple function $f(x)=x^{2} +2$ 
$f(1) = 3$, $P(1,3)$ $\text{Domain} = \{x \in \mathbb{R}\}$
$f(x)$ is  [[Continuity#Continuity|Continuous]] at $x=1$
Because this is impossible at **all** points in the domain, we find the points that **Are not [[Continuity#Continuity|Continuous]]**
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
### Limits at Holes and [[Graphing Split Functions#Removable Discontinuity|RD's]]
You cannot directly solve these, instead, you must factor and simplify.
> "Simply" factor the equation to "remove" restrictions
> $$\begin{align}
\lim_{x\to{3}} \frac{x^{2}-9}{x-3}=\lim_{x\to{3}}\frac{\cancel{(x-3)}(x+3)}{\cancel{(x-3)}}=\lim_{x\to{3}}(x+3)=6
\end{align}$$
### With Rationals
$$\begin{align}
\lim_{x\to{16}}=\frac{\sqrt{x}-4}{x-16}\cdot{\frac{\sqrt{x}+4}{\sqrt{x}+4}}=\lim_{x\to{16}}\frac{\cancel{x-16}}{\cancel{(x-16)}(\sqrt{x}+4)}=\frac{1}{\sqrt{16}+4}=\frac{1}{8}
\end{align}$$
$$\lim_{x\to{0}}\frac{\sqrt{4-x}-\sqrt{4+x}}{x}\cdot{\frac{\sqrt{4-x}+\sqrt{4+x}}{\sqrt{4-x}+\sqrt{4+x}}}=\lim_{x\to{0}}\frac{-2\cancel{x}}{\cancel{x}(\sqrt{4-x}+\sqrt{4+x})}=\frac{-1}{2}$$
$$\lim_{x\to{0}}\frac{\frac{1}{(2+x)^{2}}-\frac{1}{4}}{x}$$ Simplify into one fraction
### Change of Variable
$$\begin{align}
\lim_{x\to{0}}&\frac{(4+x)^{3}-64}{x}\\
\text{Let }a&=x+4\\
\lim_{a\to{4}}&\frac{a^{3}-64}{a-4}\\
=\lim_{a\to{4}}&\frac{\cancel{(a-4)}(a^{2}+4a+16)}{\cancel{a-4}}=48
\end{align}$$