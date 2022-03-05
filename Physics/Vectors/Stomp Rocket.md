# Projectiles: Stomp Rockets
---
## <u>Variables:</u>

<u>Measured:</u> Angle, Range, Hang time

<u>Calculated:</u> Initial velocity, Maximum Height, Acceleration during launch

## <u>Data:</u>
$$\begin{align}
&\text{Angle } \theta = 46.5\degree\\
&\text{Range} = 36.9m\\
&\text{Time} = 3.54s\\
&\text{Launcher Length} = 27.0cm = 0.270m
\end{align}$$
### <u>Part 1: Trajectory Equation</u>
>Using only the trajectory equation, and **only** the range and angle calculate:
1. **Initial Velocity ($\vec{v_o}$)**
$y=0m \text{ when } x=36.9m$ 
$$\begin{align}
&\text{Range}=36.9m\\
&\theta=46.5\degree\\
&y=x\tan{\theta}- \frac{4.90x^{2}}{\vec{v_{o}}^{2}\cos^{2}{\theta}}\\
&0=36.9\tan{46.5\degree}- \frac{4.90\cdot36.9^{2}}{\vec{v_{o}}^{2}\cos^{2}{46.5\degree}}\\\\
&36.9\tan{46.5\degree}=\frac{49.0\cdot36.9^{2}}{\vec{v_{o}}^{2}\cos^{2}{46.5\degree}}\\
&\vec{v_{o}}^{2} = \frac{4.90\cdot36.9^{2}}{cos^{2}{46.5\degree}36.9\tan{46.5\degree}}\\
&\therefore \vec{v_{o}}=\sqrt{\frac{4.90\cdot36.9}{cos^{2}{46.5\degree}tan{46.5\degree}}}\\
&=19.0\text{ m/s}
\end{align}$$
2. **Maximum Height**
Point of max is when $x=\frac{\text{Range}}{2}$ 
$$\begin{align}
&y=x\tan{\theta}-\frac{4.90x^{2}}{\vec{v_{o}}^{2}cos^{2}{\theta}}\\
&y = 18.45\tan{46.5\degree} - \frac{4.90\cdot18.45^{2}}{19.0^{2}\cos^{2}{46.5\degree}}\\
&y = 9.72m
\end{align}$$
### <u>Part 2: Equations of Motion</u>
> **Without** using the trajectory equation and **only** using hang time and angle, calculate:
1. **Initial Velocity**
Vertical Velocity $=0$ when $\Delta t= \frac{\text{Hangtime}}{2}$ 
$$\begin{align}
&\vec{a}= \frac{\Delta\vec{v}}{\Delta t}\\
&\Delta\vec{v}=\vec{a}\Delta t\\
&\Delta\vec{v_{v}} = \vec{v_{v2}} - \vec{v_{v1}}\\
&\vec{v_{v2}} = 0\\
&\therefore \vec{v_{v1}} = \cancel{\vec{v_{v2}}} + \vec{a}\Delta t\\
&\vec{a} = 9.80 \text{ m/s}^2\\
&\Delta t=1.77s\\
&\vec{v_{v1}} = 9.80\cdot1.77=17.3\text{m/s}\\
&
\end{align}$$
$$\begin{align}
&\vec{v_{v1}}=\vec{v_o}\sin{\theta}\\
&\vec{v_{o}}= \frac{\vec{v_{v1}}}{\sin{\theta}}\\
&\vec{v_{o}}=23.9\text{m/s}
\end{align}$$
3. **Maximum Height**
$$\begin{align}
&\Delta\vec{d} = \vec{v_{o}}\Delta t + \frac{1}{2}\vec{a}\Delta t^{2}
\end{align}$$