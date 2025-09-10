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
$$
\operatorname{proj}_{a}b
$$

$$\text{scalar length of a projection: } \newline \frac{a\cdot b}{||a||}$$


$$
\text{vector of a projection: } \frac{a\cdot b}{||a||^2}\cdot \vec{a}
$$

orthogonal to projection: 

$$
\operatorname{orth}_{a}b= b -\operatorname{proj}_{ a}b
$$


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



12.4 Cross Product
---
(a,b,c are vectors)

$$
{a}\times {b} = \quad <a_{2}b_{3}-a_{3}b_{2}, \text{ } \text{ } a_{3}b_{1}-a_{1}b_{3}, \text{ } \text{ }a_{1}b_{2}-a_{2}b_{1} >
$$
$$
a\times b= \det \begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
a_{1} & a_{2} & a_{3}  \\
b_{1}&b_{2}&b_{3}
\end{vmatrix}

$$


as governed by the right hand rule: 

$$
\text{Theorem: } a\times b \text{ is orthogonal to both } {a} \text{ and } {b} 
$$


$$
\text{Theorem: } a \times b = -b \times a
$$

$$
\text{ want to find }||a\times b||^2
$$
$$
\text{expanding from our definition of } a\times b \text{:}
$$
$$
 a_{2}^{2}\cdot b_{3}^{2}+a_{3}^{2}\cdot {2}^{2}-2a_{2}\cdot  a_{3}\cdot  b_{2} \cdot  b_{3}
$$
$$
+a_{3}^{2} \cdot b_{1}^{2}+a_{1}^{2} \cdot b_{3}^{2}-2a_{1} \cdot a_{3}  \cdot b_{1}  \cdot b_{3}
$$
$$
+a_{1}^{2}  \cdot b_{2}^{2}+a_{2}^{2}  \cdot b_{1}^{2}-2a_{1} \cdot a_{2}  \cdot b_{1} \cdot b_{2}
$$

add and subtract to the equation:
$$
+a_{1}^{2} b_{1}^{2} + a_{2}^{2}b_{2}^{2} + a_{3}^{2}b_{3}^{2}  -a_{1}^{2} b_{1}^{2} - a_{2}^{2}b_{2}^{2} - a_{3}^{2}b_{3}^{2} 
$$
giving:
$$
(a_{1}^{2}+a_{2}^{2}+a_{3}^{2})(b_{1}^{2}+b_{2}^{2}+b_{3}^{2})-(a_{1}b_{1}+a_{2}b_{2}+a_{3}b_{3})^2
$$
$$
(a_{1}b_{1}+a_{2}b_{2}+a_{3}b_{3})^2 \text{ is the dot product of a and b squared}
$$

which is 
$$
||a||^{2}||b||^{2}-\cos ^{2}\theta
$$

$$
(a_{1}^{2}+a_{2}^{2}+a_{3}^{2}),(b_{1}^{2}+b_{2}^{2}+b_{3}^{2})
$$
these are just are just 
$$
||a||^2, ||b||^2
$$
so we have
$$
||a||^2  ||b||^2 - ||a||^{2}||b||^{2}-\cos ^{2}\theta
$$

$$
\text{simplifies to: } ||a||^{2}||b||^{2}\sin ^{2}(\theta)
$$
so

$$
||a\times b||= ||a||||b||\sin \theta
$$

this is also the area of the parallelogram formed by a and b

$$
\text{Theorem: } (da)\times b=d(a\times b)= a\times(db)
$$

$$
\text{Theorem: } a\times (b+c) = (a \times b) +(a\times c)
$$

$$
\text{Theorem: } a \cdot (b\times c) =(a\times b) \cdot c
$$

volume of a parallellopiped (a.k.a magnitude of scalar triple product):

$$
||a||\cdot||b\times c||\cos \alpha \text{ where a,b,c are interchangeable}
$$


actual scalar product

$$
a \cdot (b\times c)
$$
(you can do this with a 3x3 determinant if you want)


$$
\text{Theorem: } a \times (b \times c) =b(a\cdot c) -c(a\cdot b)
$$
(i don't think this was proven in class)

Physics application, torque:

$$
\tau =r \times F
$$


12.5 Equations of Lines and Planes in Space
---

$$
\vec{r} = \vec{r_{0}} + t\vec{v}
$$
$$
\left( \begin{matrix}x  \\
y \\
 z \\


\end{matrix}\right) 

= \left( \begin{matrix}x_{0}  \\
y_{0} \\
 z_{0} \\

\end{matrix}\right) 
+ \left( \begin{matrix}a  \\
b \\
 c \\
\end{matrix}\right) \cdot t
$$
in parametric form
$$
\begin{matrix}
x = x_{0}+at \\
y=y_{0}+bt \\
z=z_{0}+ct
\end{matrix}
$$


so 
$$
t = \frac{x-x_{0}}{a} = \frac{y-y_{0}}{b} = \frac{z-z_{0}}{c}
$$


given two points 
$$
\vec{r_{0}}  \text{ and } \vec{r_{1}}
$$

$$
\vec{r_{1}- r_{0}} = \left< x_{1}-x_{0} , y_{1}- y_{0}, z_{1}-z_{0}   \right> 
$$

** this is wrong i thinkg** define r0 
$$
r = r_{0} + v_{0} \cdot t
$$


for planes 
- a plane can be defined by 1 normal vector perpendicular 
$$
\text{ where } \vec{n} \text{ is the normal vector}
$$
so
$$
\vec{n} \cdot ( r- r_{0})= 0
$$
point normal form:
$$
a(x-x_{0}) + b(y-y_{0}) +c(z-z_{0})= 0
$$
standard form: 
$$
ax+by + cz + d =0 \text{ where } d= -ax_{0}-by_{0}-cz_{0}
$$

take some point off the plane 
$$
 p_{0} = \left( x_{1},y_{1},z_{1} \right) 
$$

WTF: distance from point to plane 
to do 
- project vec from point onto the normal vector of the plane, 
	- evaluate magnitude 

$$
\frac{\vec{n} \cdot r_{0}P_{1}}{||n||}
$$
and this is just (using the point normal eq)

$$
\frac{a(x_{1}-x_{0}) +b(y_{1}-y_{0}) + c(z_{1}-z_{0})}{^\sqrt{ a^2+b^{2}+c^{2} } }
$$


