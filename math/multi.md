multi
=====
- Category: math
- Tags: math, arsenau
- Created: 2025-07-25 @ 16:23:58-04:00

12.1 - 3 Dimensional Coordinate system
---

let 

$$
<a,b,c> = \vec{v}
$$

projection of v onto the xz plane 

$$
<a,0,c>
$$

sphere with vector as the radius

$$
(x-x_{1})^2 +(y-y_{1})^2+(z-z_{1})^2 = R^2
$$

to get the unit vector, divide the vector by its magnitude

$$
\hat{v} \text{ is the unit vector for } \vec{v}
$$


$$
\hat{v}= \frac{v}{||v||}
$$

usually don't rationalize

12.3 dot product
---


$$
\vec{a} = <a_{1},a_{2},a_{3}>
$$


$$
\vec{b} = <b_{1},b_{2},b_{3}>
$$



$$
\vec{a}\cdot    \vec{b} = a_{1}b_{1}+a_{2}b_{2}+a_{3}b_{3}
$$


$$
\text{properties: (} a,b,c \text{ are vectors)}
$$


$$
\text{1. } a\cdot a = ||a||^2
$$

$$
\text{2. }a\cdot b = b\cdot a
$$


$$
\text{3. } a\cdot (b+c)= a\cdot b + a \cdot c
$$


$$
\text{4. }(ka)\cdot b=k(a\cdot b)=a\cdot(kb)
$$


$$
\text{5. }\vec{0}\cdot a= 0
$$


$$
\text{theorem: }
\newline a\cdot b = ||a||\cdot||b|| \cos \theta
$$

prove this thm at home


projections:


$$\text{scalar length of a projection: } \newline \frac{a\cdot b}{||a||}$$


$$
\text{vector of a projection: } \frac{a\cdot b}{||a||^2}\cdot \vec{a}
$$


\[
\text{orthogonal to projection: }\quad \operatorname{orth}_{\mathbf{a}}(\mathbf{b}) = \mathbf{b} - \operatorname{proj}_{\mathbf{a}}(\mathbf{b})
\]


angles in the xyz plane: (alpha is angle to x, beta angle to y, gamma angle to z)

$$
\frac{a_{1}}{||a||}= \cos \alpha
$$

$$
\frac{a_{2}}{||a||}= \cos \beta
$$


$$
\frac{a_{3}}{||a||}= \cos \gamma
$$

physics application 

$$
W = F\cdot D = ||F_{component}||\times||D||
$$