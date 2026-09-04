---
title: Why Axioms
template: default
---

To be precise in the definition of a **Vector Space**, we *must* specify a precise set of **rules** that this space and its elements satisfy. 

These rules are called **axioms**.

An example
### Peano axioms

The natural numbers $\mathbb{N}$ are characterized by:

1. **Zero**

   $0 \in \mathbb{N}$

2. **Successor**

   There exists a function
   $$S : \mathbb{N} \rightarrow \mathbb{N}$$
   called the successor function.

3. **Zero has no predecessor**

   $$\forall n \in \mathbb{N},\quad S(n) \neq 0$$

4. **The successor function is injective**

   $$\forall n,m \in \mathbb{N},\quad
   S(n)=S(m) \Rightarrow n=m$$

5. **Principle of induction**

   For every subset $A \subseteq \mathbb{N}$,
   $$0\in A \quad\land\quad
   \forall n\in\mathbb{N},\,
   (n\in A \Rightarrow S(n)\in A)
   \quad\Rightarrow\quad
   A=\mathbb{N}.$$
