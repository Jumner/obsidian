#derivatives 
# Rate of Change
---
> The rate of change is nothing but the Slope of the Tangent $\frac{df}{dx}$ 

## Average Rate of Change
> The average rate of change has a concrete change in x ($d x$) it is the slope of the **secant** between **two Points**
## Instantaneous Rate of Change
> The ratio that $\frac{\Delta f}{\Delta x}$ approaches as $\Delta x\to0$. This lim ($\lim_{\Delta x\to{0}}$) is hidden within the $\frac{df}{dx}$ notation
## Formal Solution
> $$\begin{align}
\text{let } P&(11,f(11))=(11,3)\\
Q&(11+h,f(11+h))=(11+h,\sqrt{9+h})\\
\lim_{h\to{0}}& \frac{\sqrt{9+h}-3}{h}\\
=\lim_{h\to{0}}&\frac{\cancel{9}+\cancel{h}-\cancel{9}}{\cancel{h}(\sqrt{9+h}+3)}\\
=\lim_{h\to{0}}& \frac{1}{\sqrt{9+h}+3}=\frac{1}{6}
\end{align}$$