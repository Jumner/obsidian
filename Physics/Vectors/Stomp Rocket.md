# Projectiles: Stomp Rockets
---
## <u>Variables:</u>

<u>Measured:</u> Angle, Range, Hang time

<u>Calculated:</u> Initial velocity, Maximum Height, Acceleration during launch

## <u>Data:</u>
$$\begin{align}
&\text{Angle } \theta = 46.5\degree\\
&\text{Range} = 36.9\text{ m}\\
&\text{Time} = 3.54\text{ s}\\
&\text{Launcher Length} = 27.0 \text{ cm} = 0.270 \text{ m}
\end{align}$$
## <u>Part 1: Trajectory Equation</u>
>Using only the trajectory equation, and **only** the range and angle calculate:

a. **Initial Velocity ($\vec{v_o}$)**
$y=0\text{ m}, x=36.9\text{ m}$ 
$$\begin{align}
&\text{Range}=36.9\text{ m}\\
&\theta=46.5\degree\\
&y=x\tan{\theta}- \frac{4.90x^{2}}{\vec{v_{o}}^{2}\cos^{2}{\theta}}\\\\
&0=x\tan{\theta}- \frac{4.90x^{2}}{\vec{v_{o}}^{2}\cos^{2}{\theta}}\\\\
&x\tan{\theta}=\frac{4.90x^{2}}{\vec{v_{o}}^{2}\cos^{2}{\theta}}\\\\
&\vec{v_{o}}^{2} = \frac{4.90x^{\cancel{2}}}{\cancel{x}\cos^{2}{\theta}\tan{\theta}}\\\\
& \vec{v_{o}}=\sqrt{\frac{4.90x}{\cos^{2}{\theta}\tan{\theta}}}\\\\
&\therefore \vec{v_{o}}=\sqrt{\frac{4.90\cdot36.9}{cos^{2}{46.5\degree}tan{46.5\degree}}}\\
&=19.0\text{ m/s}
\end{align}$$
b. **Maximum Height**
Point of max height is when $x=\frac{\text{Range}}{2}$ 
$$\begin{align}
&y=x\tan{\theta}-\frac{4.90x^{2}}{\vec{v_{o}}^{2}cos^{2}{\theta}}\\
&y = 18.45\tan{46.5\degree} - \frac{4.90\cdot18.45^{2}}{19.0^{2}\cos^{2}{46.5\degree}}\\
&y = 9.72\text{ m}
\end{align}$$
## <u>Part 2: Equations of Motion</u>
> **Without** using the trajectory equation and **only** using hang time and angle, calculate:

a. **Initial Velocity**
Vertical Velocity $=0$ when $\Delta t= \frac{\text{Hangtime}}{2}$ 
$$\begin{align}
&\vec{a}= \frac{\Delta\vec{v}}{\Delta t}\\
&\Delta\vec{v}=\vec{a}\Delta t\\
&\Delta\vec{v_{v}} = \vec{v_{v2}} - \vec{v_{v1}}\\
&\vec{v_{v2}} = 0\\
&\vec{v_{v1}}=\cancel{\vec{v_{v2}}}-\Delta\vec{v_{v}}\\
&\therefore \vec{v_{v1}} = -\vec{a}\Delta t\\
&\vec{a} = -9.80 \text{ m/s}^{2}[\uparrow]\\
&\Delta t=1.77s\\
&\vec{v_{v1}} = -(-9.80\cdot1.77)=17.3\text{m/s}[\uparrow]\\
&
\end{align}$$
$$\begin{align}
&\vec{v_{v1}}=\vec{v_o}\sin{\theta}\\
&\vec{v_{o}}= \frac{\vec{v_{v1}}}{\sin{\theta}}\\
&\vec{v_{o}}=23.9\text{m/s}[\rightarrow46.5\degree\uparrow]
\end{align}$$
b. **Maximum Height**
Point of max height is when $\Delta t = \frac{\text{Hangtime}}{2}$
$$
\begin{align}
&\Delta\vec{d} = \vec{v_{o}}\Delta t + \frac{1}{2}\vec{a}\Delta t^{2}\\
&\Delta\vec{d_v} = \vec{v_{v1}}\Delta t + \frac{1}{2}\vec{a}\Delta t^{2}\\
&\vec{a} = -9.80\text{ m/s}^{2}\text{ } [\uparrow]\\
&\Delta\vec{d_{v}} =\vec{v_{v1}}\Delta t - 4.90\Delta t^{2}\\\\
&\Delta t = \frac{3.54}{2}=1.77\text{ s} \\
&\vec{v_{v1}} = 17.3\text{ m/s }[\uparrow]\\\\
&\Delta\vec{d_{v}}=17.3\cdot1.77-4.90\cdot1.77^{2}\\
&=15.4\text{ m }[\uparrow]
\end{align}$$
---

## <u>Part 3: Consistency</u>
1. **Calculate the average of 1a and 2a. Now calculate the consistency of your data:**
$$
\begin{align}
&\text{Average of }1a\text{ and }2a = \frac{1a+2a}{2}\\
&=\frac{19.0+23.9}{2} = 21.5 \text{ ms} [\rightarrow46.5\degree\uparrow]\\\\
&\text{consistency}=100 - \frac{|(1a-2a)|}{\text{Average of }1a\text{ and } 2a}\cdot100\\
&=100 - \frac{|(19.0-23.9)|}{21.5}\cdot100\\
&=77\%
\end{align}
$$

2. **Calculate the average of 1b and 2b. Now calculate the consistency of your data:**
$$
\begin{align}
&\text{Average of }1b\text{ and }2b = \frac{1b+2b}{2}\\
&=\frac{9.72+15.4}{2} = 12.5 \text{ m}\\\\
&\text{consistency}=100 - \frac{|(1b-2b)|}{\text{Average of } 1b \text{ and } 2b}\cdot100\\
&=100 - \frac{|(9.72-15.4)|}{12.5}\cdot100\\
&=55\%
\end{align}
$$
---

## <u>Part 4: Acceleration</u>
> Calculate the **acceleration** of the rocket while on the tube launcher using the **length of the tube** and the **average of 1a and 2a**.
$$
\begin{align}
&\vec{v_{1}} = 0 \text{ m/s}\\
&\vec{v_{2}} = \text{average of }1a\text{ and }2a = 21.5 \text{ m/s } [\rightarrow46.5\degree\uparrow ]\\\\
&\Delta\vec{d} = 27.0\text{ cm}=0.270\text{ m}\\
&\Delta\vec{d} = \frac{\vec{v_{2}}^2-\vec{v_{1}}^{2}}{2\vec{a}}\\\\
&\therefore \vec{a} = \frac{\vec{v_{2}}^{2} \cancel{- \vec{v_{1}}^{2}}}{2\Delta\vec{d}}\\\\\\
&\vec{a} = \frac{21.5^{2}}{2\cdot0.270}\\
&=854 \text{ m/s}^2\text{ }[\rightarrow46.5\degree\uparrow]\\
&
\end{align}
$$
## <u>Part 5: The difference</u>
> The answers from **Part 1** and **Part 2** are **different**
> Describe why the two different methods give **different values**.

The reason for the difference comes down to how they **fit a parabola** to the **measured data** as well as how **error** affects them.

### The source of error
The main **source of error** in this lab is **drag**. As the rocket flies through the **air**, it is forced to slow down due to air resistance. The **inconsistencies** are observed because air resistance effects each of the equations **differently**. 

Both equations assume no drag and create **perfect parabola**. Let's look at how the 2 equations work.

### Part 1
Part 1 uses the **trajectory equation**. This equation takes the **launch angle** and the **range** then fits a parabola to it. From this **fitted** parabola, it determines the velocity and max height.
>Here is a diagram of how this equation works.
![[pt1.png]]
It is clear that the parabola is fit to the **range**.
### Part 2
Part 2 uses the **Equations of motion**. These equations fit a parabola to the **hang time**. These equations essentially **find the parabola with the same hang time** as was observed. 
> Here is a diagram of how these equations work.
![[pt2.png]]
The parabola is fit to the **hang time**.
### Conclusion
In conclusion, the observed **inconsistencies** are because the two methods are affected by **error** differently.