---
layout: post
title: "Notes on Number Theory ---- Fermat's Dream ---- 1"
---

# Structure of Rational Points on an Elliptic Curve

Although Fermat claimed that he had a brilliant idea of how to prove the non-existence of integer solutions of the equation $x^n + y^n = z^n$ for $n\geqslant 3$ in a seemingly arrogant manner, he did give a proof for a simple case of $n = 4$. Here we formulate his proof in modern languages.

A simple transformation converts the equation 

$$
x^4 + y^4 = z^4
$$

into 
$$
\left(\frac{x^2z}{y^3}\right)^2 = \left(\frac{z^2}{y^2}\right)^3 - \frac{z^2}{y^2}
$$
Using different letters, this is essentially the elliptic curve $b^2 = a^3 - a$. 
If the equation $x^4 + y^4 = z^4$ has any nontrivial integer solution, then the solution boils down to a rational point on the above elliptic curve. 

## Elliptic curves

A rough definition of elliptic curves is polynomial equations of the form $y^2 = (x - a)(x - b)(x - c)$ for distinct $a, b, $ and $c$.