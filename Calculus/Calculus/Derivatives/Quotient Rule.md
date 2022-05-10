#derivatives 
# Quotient Rule
---
> The [[#Quotient Rule]] determines how to find the [[Derivative#Definition Of the Derivative|Derivative]] of a fraction
> $$\frac{f(x)}{g(x)}'=\frac{f'(x)g(x)-f(x)g'(x)}{g(x)^{2}}$$ 

## Derivation
> It can be derived from the [[Chain Rule#Chain Rule]]
>$$\begin{align}
\frac{f(x)}{g(x)}&=f(x)\cdot \frac{1}{g(x)}\\
\frac{f(x)}{g(x)}'&=f(x)\cdot \frac{1}{g(x)}'+f'(x)\cdot \frac{1}{g(x)}\\
&=f(x)\cdot \frac{-1}{g(x)^{2}}g'(x)+ \frac{f'(x)}{g(x)}\\
&=\frac{-f(x)g'(x)}{g(x)^{2}}+ \frac{f'(x)g(x)}{g(x)^{2}}\\\\
\therefore&=\frac{f'(x)g(x)-f(x)g'(x)}{g(x)^{2}}
\end{align}$$
