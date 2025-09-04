diffeq
=====

- Category: math
- Tags: arsenau
- Created: 2025-09-02 @ 12:52:44-4:00

Section 2.1
---

1.

   $$
   F = MA
   $$

2.

   $$
   A = P - K\,V
   $$

where \(P\) is the initial acceleration (≈ 11.0 for Usain), \(V_{\max}\) is max velocity (≈ 12.2 for Usain), and \(K\) depends on the person.

So we could find \(k = 11/12.2\). Using (1) and (2),
$$
MA = MP - MKV,
$$
let \(A = V'\). Usain equation:
$$
V' + \frac{11}{12.2} V = 11.0.
$$

This is a first-order linear ODE.

General form:
$$
v' + K v = P.
$$

Integrating factor:
$$
\mu(t) = e^{Kt}.
$$

Distribute the integrating factor:
$$
(e^{Kt} v)' = P\,e^{Kt}.
$$

Integrate both sides:
$$
v(t) = \frac{P}{K} + C e^{-K t}.
$$

For Usain:
$$
V(t) = 12.2 + C\,e^{-(11/12.2)t}.
$$

Now let \(p(t), q(t)\) be non-constants
