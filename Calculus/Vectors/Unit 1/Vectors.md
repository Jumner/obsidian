#vectors 
#calculus-unit-1 
# Vector
Vectors have both [[#Direction]] and [[#Magnitude]]. 
## Examples
> Velocity, displacement, force, weight
## Direction
Where the [[#Vector]] points to.
### True bearing
> Measured from due north. Measured going counter clockwise
### Conventional Bearing
> Angle between 2 closest marks. Example, N 30$\degree$ E -> Start at north go 30 degrees towards east
### Tail to tail
> The angle between 2 vector placed tail to tail
> This value is negative if the vector is clockwise relative to the other vector
## Magnitude
The length of the vector. Independent of [[#Direction]]
Represented by a single number
## Equal / Equivalent vectors
Vectors are equal when their [[#Direction|Directions]] and [[#Magnitude|Magnitudes]] are equal
## Geometry
Geometrically, they can be expressed as a line segment with an arrow. This is called a **directed** line segment. ^61c47d
## Notation
Vectors are written with an arrow over top
$$\overrightarrow {AB} \text{ or } \vec{v}$$
### Magnitude
The **absolute** of the vector. The length
$$\left | \vec{v} \right |$$
### Direction
What direction the vector is pointed.
Notated with $\theta\degree$   
### Parallel vectors
When 2 vectors are **Parallel** or **Collinear**
$$\vec v\, \textbackslash\textbackslash\, \vec u$$
### Unit vectors
Unit vectors are notated with a hat
$$\hat v = \frac{\vec v}{\left| \vec v \right |}$$
Called **v hat**
> Note that a zero vector would require dividing by zero
> This is why [[#Direction]]  is not defined

## Opposite vectors
Vectors are opposite when their [[#Direction|Directions]] are opposite and their [[#Magnitude|Magnitudes]] are equal
## Parallel / Collinear Vectors
Vectors are **collinear** when their [[#Direction|Directions]] are either the **same** or **opposite**.
> [[#Magnitude]] is not important
## Zero vector
The zero vector has a [[#Magnitude]] of **zero** and **Not Defined** [[#Direction]]
## Unit vector
A vector with a [[#Magnitude]] of **1**. The [[#Direction]] is **not important**
Every [[#Vector]] has a [[#Unit vector]] besides a [[#Zero vector]]. See [[#Unit vectors|Explanation]]
> [[#Unit vectors|Notated]] with a hat

---
## Multiplying and Dividing by [[Scalers#Scaler|Scaler]]
The [[#Direction]] is unchanged but the [[#Magnitude]] is scaled
$$-\vec v = -1 \cdot \vec v$$
$$\left| k\vec{v} \right| = k\left|\vec{v}\right|$$
if k > 0, direction **remains**
if k < 0, direction **flips**
if k = 0, becomes **[[#Zero vector]]**
- ### [[Random helpers#Commutativity|Commutativity]] -> **True**
- ### [[Random helpers#Associativity|Associativity]] -> **True**
- ### [[Random helpers#Distributivity|Distributivity]] -> **True**
## Adding and Subtracting [[#Vector|Vectors]]
### Adding [[#Vector|Vectors]]
sum of vectors is called the **Resultant vector**
Vectors are placed **tip to tail** (Sequentially)
Their components can also be summed individually
- #### [[Random helpers#Commutativity|Commutativity]] -> **True**
- #### [[Random helpers#Associativity|Associativity]] -> **True**
### Subtracting [[#Vector|Vectors]]
Can be simplified as an [[#Adding Vector Vectors|Addition]] and **inversion**
$$\vec{u}-\vec{v} = \vec{u}+(-\vec{v}) = \vec{u}+(-1\cdot\vec{v})$$
The inverted vector is placed tip to tail just like [[#Adding Vector Vectors|Addition]] 
- #### [[Random helpers#Commutativity|Commutativity]] -> **False**
- #### [[Random helpers#Associativity|Associativity]] -> **True**