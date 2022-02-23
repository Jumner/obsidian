# Dot Product
---
Unlike [[Vectors#Adding and Subtracting Vector Vectors|Adding\Subtracting]], and [[Vectors#Multiplying and Dividing by Scalers Scaler Scaler|Scaler Multiplication]], the result of [[#Dot Product]] is a [[Scalers|Scaler]].
This product is also known as the **Scaler Product** or the **Inner Product**
![[Pasted image 20220222134914.png]]
Always remember that $\vec{u}\perp\vec{v}, \vec{u}\cdot\vec{v} = 0$ 
## Notation
$\vec{u}$ dot $\vec{v}$ = $\vec{u}\cdot\vec{v}$ 
$\vec{u}\cdot\vec{v} = |\vec{u}||\vec{v}|\cos{\theta} = u_{1}v_{1}+u_{2}v_{2}$ 
$\theta$ is is the angle tail to tail.
## Solving for $\theta$
Because $\vec{u}\cdot\vec{v} = |\vec{u}||\vec{v}|\cos{\theta}$, $\cos{\theta} =\frac{u_{1}v_{1}+u_{2}v_{2}}{|\vec{u}||\vec{v}|}$, $\therefore \theta=cos^{-1}({\frac{u_{1}v_{1}+u_{2}v_{2}}{|\vec{u}||\vec{v}|}})$

## Use with [[Algebraic Vectors#Vectors Direction Direction Angles|Direction Angles]]
$\vec{v} = (a, b, c)$
$\cos{\alpha} = \frac{\vec{v}\cdot\hat{i}}{|\vec{v}||\hat{i}|} = \frac{a}{|\vec{v}|}$  
$\cos{\beta} = \frac{\vec{v}\cdot\hat{j}}{|\vec{v}||\hat{j}|} = \frac{b}{|\vec{v}|}$  
$\cos{\gamma} = \frac{\vec{v}\cdot\hat{k}}{|\vec{v}||\hat{k}|} = \frac{c}{|\vec{v}|}$  
## Properties
$\vec{a}\cdot\vec{a} = |\vec{a}|^2$ 
### [[Random helpers#Commutativity|Commutativity]] -> True
### [[Random helpers#Distributivity|Distributivity]] with addition
#### $\vec{a}\cdot(\vec{b}+\vec{c})=\vec{a}\cdot\vec{b}+\vec{a}\cdot\vec{b}$ 
### [[Random helpers#Distributivity]] with scaler multiplication
$(k\vec{a})\cdot\vec{b}=k(\vec{a}\cdot\vec{b})=\vec{a}\cdot(k\vec{b})$

## Hard problem
$$
\begin{align}
&\vec{v} = (2,-3,1)\\
&\vec{u} = (1,1,1)\\
&0 = \vec{u}\cdot\vec{w} = \vec{v}\cdot\vec{w}\\
&2x-3y+z = 0\\
&x+y+z = 0\\
&z=3y-2x\\
&4y-x=0\\
&y=\frac{x}{4}\\
&z=3\frac{x}{4}-2x =\frac{-5x}{4}\\\\
&\vec{w} = (x,\frac{x}{4}, \frac{-5x}{4})\\
&\vec{w} = (4, 1, -5)
\end{align}
$$