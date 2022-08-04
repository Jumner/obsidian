#derivatives 
# Derivatives of Exponentials
---
> This is a tough one.
> To understand this you must first understand a few ideas

> - The derivative of an exponential **is proportional to itself** $$\dot{2^{x}}=k2^{x}$$
> - The derivative of $e^{x}$ **is equal to** $e^{x}$ 
> - The proportionality constant is equal to the **natural log** of the base $$\begin{align}
\dot{2^{x}}=k2^{x}&,k=\ln{2}\\
\therefore \dot{2^{x}}&=\ln{2}\cdot2^{x}
\end{align}$$  
## Mathematically (chain rule)
>$$\begin{align}
2^{x}&=(e^{\ln{2}})^{x}\\
&=e^{\ln2\cdot x}\\
\dot{2^{x}}&=e^{\ln2\cdot x}\cdot\dot{\ln2\cdot x}\\
&=e^{\ln2\cdot x}\cdot\ln2\\
&=2^{x}\cdot\ln2
\end{align}$$

### Why Does The Base Matter?
> The reason the base matters is that the average rate of change across 1 unit **IS** equal to itself. But as the aroc approaches the iroc, this will change. 

---
# Derivatives of Logarithms
---
> $$\dot{\log_{a}x}=\frac{1}{x\ln{a}}$$
> $$\begin{align}
y&=\log_{b}x\\
b^{y}&=x\\
\dot{b^{y}}&=\dot{x}\\
b^{y}\ln{b}\cdot\dot{y}&=1\\
\dot{y}&= \frac{1}{x\ln{b}}
\end{align}$$
## Natural Log
> The derivative of natural log of x is just 1/x
> $$\dot{\ln(x)}=\frac{1}{x}$$

