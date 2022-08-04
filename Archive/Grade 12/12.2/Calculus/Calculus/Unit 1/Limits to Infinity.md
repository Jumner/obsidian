#limits 
# Limits to Infinity
---
## DNE
$\frac{\#}{0}=\pm\infty$ **Asymptote**
$\infty+\infty=\infty$
$\frac{\pm\infty}{0}=\pm\infty$ 
**Discontinuous**
![[Limits#Left and Right Hand Limit (RH, LH)]]
## Infinite Limits
Infinite Limits occur around **Vertical Asymptotes** and $\lim_{x\to{a}}f(x)=\pm\infty$ 
### Example
$$\begin{align}
\lim_{x\to{0}}& \frac{1}{x^{2}}=\frac{1}{0^{2}}=\pm \infty\\
&=\infty\\
&=DNE
\end{align}$$
$$\begin{align}
LH&= \lim_{x\to{0}^{-}} \frac{1}{x}=\frac{1}{-0}=-\infty\\
RH&= \lim_{x\to{0}^{+}} \frac{1}{x}=\frac{1}{0}=\infty\\
LH&\ne RH\\
\lim_{x\to{0}}& \frac{1}{x}=DNE
\end{align}$$
## Limits at Infinity
$$\lim_{x\to{\infty}}f(x), \lim_{x\to{-\infty}}f(x)$$
$f(x)$ has a **Horizontal Asymptote** (HA) if $\lim_{x\to{-\infty}}f(x)=L$ or $\lim_{x\to{\infty}}f(x)=L$ 
### Theorem
$$\begin{align}
\lim_{x\to{-\infty}}& \frac{1}{x^{r}} = \frac{1}{-\infty^{r}}=-0\\
\lim_{x\to{\infty}}& \frac{1}{x^{r}} = \frac{1}{+\infty^{r}}=+0
\end{align}$$
- The **negative zero** means that it **approaches from below**
- the **positive zero** means that it **approaches from above**
When you have **x** in the **numerator and denominator**, factor it until you get to the [[#Theorem]] above. (**Try dividing by $\frac{x^{2}}{x^{2}}$**)
$$\begin{align}
\lim_{x\to{\infty}}\frac{x^{2}3-\frac{1}{x}- \frac{2}{x^{2}}}{x^{2}(5+ \frac{4}{x}+ \frac{1}{x^{2}})}= \frac{3-0-0}{5+0+0}=\frac{3}{5}
\end{align}$$