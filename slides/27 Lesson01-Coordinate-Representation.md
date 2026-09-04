---
title: Coordinate Representations of Vector Spaces
template: default
---

Let us try another representation

$$
\mathbf{b}_1=\mathbf{ (1,1)}, \quad \mathbf{b}_2=\mathbf{ (-1,1)}
$$

can we represent any vector as?

$$
\mathbf{ (x_1,x_2)}= c_1 \mathbf{ (1,1)}+ c_2 \mathbf{ (-1,1)}
$$

And indeed we can

$$
\mathbf{ (x_1,x_2)}= \frac{1}{2} (x_1+x_2)\cdot \mathbf{ (1,1)}+ \frac{1}{2} (-x_1+x_2)\cdot\mathbf{ (-1,1)}
$$

Because
$$
\begin{aligned}
&\frac{1}{2} (x_1+x_2)\cdot \mathbf{ (1,1)}+ \frac{1}{2} (-x_1+x_2)\cdot \mathbf{ (-1,1)}\\
&= (\frac{1}{2} (x_1+x_2)-\frac{1}{2} (-x_1+x_2),\frac{1}{2} (x_1+x_2)+\frac{1}{2} (-x_1+x_2))=\mathbf{ (x_1,x_2)}
\end{aligned}
$$

**uniqueness is left as an exercise** by verifying linear independence
