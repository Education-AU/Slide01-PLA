---
title: Exercise 8_3
template: default
---

<div class="center-left">
Go through the vectors from the standard basis in the following way to build the final basis:


Consider the vectors $\{ \mathbf{b}_1,\mathbf{b}_2 \}$ initially as the **previous vectors**


1. If the vector $\mathbf{e}_i$ is a linear combination of the **previous vectors** throw it away since then it can be expressed by the previous vectors and is redundant.
2. If the vector $\mathbf{e}_i$ cannot be expressed as a linear combination of the **previous vectors**. Then **add** it to the **previous** vectors.


Using this procedure you will end up with a set
$$
\{ \mathbf{b}_1 ,\mathbf{b}_2,\mathbf{e}_i \dots \}
$$
which is a basis. In this particular case you should only choose to add **one** $\mathbf{e}_i$.

</div>

What we obtain by this construction is in fact a theorem:

<div class="center-left">
Any set of linear independent vectors can be extended to a basis of the entire vector space.
</div>