---
title: The Complex valued functions as a vector space
template: default
---
4. **Additive inverse:**<br>
   Choose as the additive inverse to any function $f\in V$ the function $-f$ <br>
   defined by $(-f)(t)=-f(t)$ for all $t\in \mathbb{R}$.<br>
   Then $(f\oplus -f)(t) = f(t)+-f(t)= 0\Rightarrow f\oplus -f=\textbf{0}$
5. **Associative multiplication**:<br>
   $((s_1\cdot s_2)\odot f)(t) = (s_1\cdot s_2)\cdot   f(t)=s_1 \cdot (s_2\cdot f)=s_1(s_2\odot f)(t)=(s_1\odot (s_2\odot f))(t)$
6. **Distribution over scalar multiplication**:<br>
   $((s_1+s_2)\odot f)(t)=(s_1+s_2)\cdot f(t)=s_1\cdot f(t)+s_2\cdot f(t)=(s_1\odot f\oplus s_2\odot f)(t)$
7. **Distribution over addition**:<br>
   $(s\odot (f_1\oplus f_2))(t)= s\odot(f_1(t)+f_2(t))=s_1\cdot f_1(t)+s\cdot f_2(t)=(s_1\odot f_1 \oplus s\odot f_2)(t)$
8. **Multiplicative identity**:<br>
   $(1\odot f)(t)=1\cdot f(t) = f(t)$

This vector space and related vector spaces are heavily used in the analysis of say linear differential equations.