---
title: The Complex valued functions as a vector space
template: default
---

We choose  $\mathbb{F}=\mathbb{C}$ and define and
for any $f_1,f_2 \in C^2[0,\infty]$ and any $s \in \mathbb{F}$
$$
\begin{aligned} (f_1\oplus f_2)(t)& = f_1 (t)+f_2 (t) \\ (s\odot f_1)(t)& = s\cdot f_1 (t)
\end{aligned}
$$
Since differentiation is linear, the such defined operations are indeed closed on $C^2[0,\infty]$

Now the axioms:

1. **Commutative addition:**<br>
   $(f_1\oplus f_2)(t)= f_1 (t)+f_2 (t)=f_2 (t)+f_1 (t)= (f_2\oplus f_1)(t)$
2. **Associative Addition:**<br>
   $(f_1\oplus f_2)\oplus f_3= (f_1 (t)+f_2 (t))+f_3 (t)=f_1 (t)+ (f_2 (t)+f_3 (t))=f_1 (t) + (f_2 (t)+f_3 (t))= (f_1\oplus (f_2\oplus f_3))(t)$
3. **Additive identity:**<br>
    Chosen as the function **0** the function that is all zero, then<br>
   $(f\oplus \text{\textbf{0}})(t)= f(t)+0=f(t)$
4. **Additive inverse:**<br>
   $(f\oplus -f)(t) = f(t)+-f(t)= \textbf{0}$