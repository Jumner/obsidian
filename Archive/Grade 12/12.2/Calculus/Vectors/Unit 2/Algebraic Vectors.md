#vectors 
#calculus-unit-2
# Algebraic [[Vectors]]
---
They are like normal [[Vectors|Geometric Vectors]] and still have [[Vectors#Direction|Direction]] and [[Vectors#Magnitude|Magnitude]]
Instead of being fully represented by these, they are represented as a ([[#X]],[[#Y]],[[#Z]]) **point** using **Coordinates**. 
The [[Vectors#^61c47d|Directed Line Segment]] is drawn from the **origin** (0,0,0) to the tip ([[#X]],[[#Y]],[[#Z]])
## Dimensionality
### One Dimensional Vectors
Can be represented on a single line

### Two Dimensional Vector
$\mathbb{R}^{2}$  Space (**Two real numbers**)
Can be represented on a plane
Angle **$\theta$** is measured **counter clockwise** from the [[#X|X Axis]] to the vector
All 2d Vectors can be represented by a linear combination of the [[#Base vectors]]
$$\vec{v} = (1,2) = \hat{i} \cdot 1 + \hat{j} \cdot2$$
### Three Dimensional Vector
$\mathbb{R}^2$ Space (**3 real numbers**)
Can be represented in 3d space as an ordered triple
All 3d vectors can be represented by a linear combination of all 3 [[#Base vectors]]
$$\vec{v} = (1, 2, 3) = \hat{i}\cdot1 + \hat{j}\cdot2 + \hat{k}\cdot3$$
#### Finding the [[Vectors#Magnitude|Magnitude]]
The pythagorean theorem extends to 3d.
$\vec{v} = (x,y,z)$
$\therefore |\vec{v}| = \sqrt{x^{2}+ y^{2}+ z^2}$ 
#### [[Vectors#Direction|Direction]] Angles
These are called **Direction angles** and are not the same as [[Euler Angles]]
$\alpha$ -> angle between $\hat{i}$ and $\vec{v}$
$\beta$ -> angle between $\hat{j}$ and $\vec{v}$
$\gamma$ -> angle between $\hat{k}$ and $\vec{v}$
##### Derivation
$\cos{\alpha} = \frac{a}{|\vec{v}|}$
$\cos{\beta} = \frac{b}{|\vec{v}|}$
$\cos{\gamma} = \frac{c}{|\vec{v}|}$
This makes it super simple with unit vectors
$\alpha = cos^{-1}a$ etc...
$\hat{v} = (cos{\alpha}, cos{\beta}, cos{\gamma})$
$cos^{2}{\alpha}= (cos{\alpha})^2$ 
$cos^{2}{\alpha} + cos^{2}{\beta} + cos^{2}{\gamma} = 1$ (unit vector not needed)

## Components
The components of a [[Vectors|Vector]] are what consists of the **coordinates**
The components of Vector $\vec{v} = (0,0)$ 

## Notation
### [[#One Dimensional Vectors]]
$\vec{v} = (-23)$
### [[#Two Dimensional Vector]]
$\mathbb{R}^{2}= \mathbb{R} \cdot \mathbb{R} = \{(x, y)| x,y \in \mathbb{R}\}$   
#### Ordered Pair Notation
$$\vec{v} = (x,y)$$
#### [[#Base vectors|Unit Vector Notation]] 
$$\vec{v} = \hat{i}\cdot x + \hat{j}\cdot y$$
#### [[Vectors#Magnitude|Magnitude]]
$|\vec{v}| = |\overrightarrow{Op}| = \sqrt{x^{2} + y^{2}}$ 
#### [[Vectors#Direction|Angle]] $\theta$ 
$$tan{\theta} = \frac{y}{x} \therefore \theta = tan^{-1}(\frac{y}{x})$$
## Equal Vectors
[[#Algebraic Vectors]] are equal when their [[#Components]] are equal
## Adding and Subtracting [[#Algebraic Vectors]]
Adding and subtracting [[#Algebraic Vectors]] is done by adding or subtracting the [[#Components]].
$\vec{u} = (4,6) \text{ and } \vec{v} = (3,-4)$
$\vec{u} + \vec{v} = (4+3, 6+-4)= (7, 2)$
### [[Random helpers#Associativity|Associativity]] -> True
### [[Random helpers#Commutativity|Commutativity]] -> True
## Multiplying and Dividing by [[Scalers#Scaler|Scalers]] 
When multiplying and dividing by a [[Scalers#Scaler|Scaler]], the [[#Components]] are scaled.
$\vec{v} = (1, 2)$
$5\vec{u} = (5\cdot1, 5\cdot2)$
### [[Random helpers#Associativity|Associativity]] -> True
### [[Random helpers#Distributivity|Distributivity]] -> True
### [[Random helpers#Commutativity|Commutativity]] -> True
# Base vectors
## X
The **X** (**$\hat{i}$**) [[Vectors#Unit vector|Unit Vector]]  points towards you
## Y
The **Y** (**$\hat{j}$**) [[Vectors#Unit vector|Unit Vector]]  points to the right
## Z
The **Z** (**$\hat{k}$**) [[Vectors#Unit vector|Unit Vector]]  points up