diffeq
=====
- Category: math 
- Tags: arsenau 
- Created: 2025-09-02 @ 12:52:44-4:00

Section 2.1
---


1.
$$
F=MA
\\

$$
2.
$$
A=P-K*Vmax
$$

where P is the initial accel -- 11.0 for usain,
Vmax, is max velocity -- 12.2 for Usain
K is a constant that depends on the person 

so we could find $$ k= 
 11/12.2 $$
using equations one and two
$$
MA = MP - MKV
$$
let
$$
 A = V'
$$
usain equation:
$$
V' + \frac{11}{12.2} V = 11.0

$$

this is a linear differential equation 
a first order one, because first derivative only
if we were to have squares, variables multiplied, it no longer is linear

let's take
$$
\frac{dy}{dt}\ + P(t)*y= q(t)
$$

we could use separation of variables 
but we're going to use integrating factor LOL


general form 
$$
v' + KV =P
$$
integrating factor
$$
I = e^{kt}
$$
distrib the integrating factor
$$
e^{kt}*v'l+ Ke^{kt}*v=Pe^{kt}
$$
This is  a product rule

integrate both sides

$$
V=\frac{P}{k}+Ce^{-kt}
$$
for usain--

$$
V=12.2+Ce^{-\frac{-11}{12.2}t}
$$


let's let p(t), q(t) not be constants
$$
y'+p(t)y=q(t)
$$
$$
I(t)=\mu(t)
$$
$$
\mu(t) y'+\mu(t)p(t)=\mu(t)q(t)
$$

take derivative

$$
\mu(t)y'+\mu'(t)y=\mu(t)q(t)
$$
$$
\mu'(t)
=\mu(t)p(t)$$
2.2
---

