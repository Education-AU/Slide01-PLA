---
title: Why Axioms
template: default
---

To be precise in the definition of a **Vector Space**, we *must* specify a precise set of **rules** that this space and its elements satisfy. 

These rules are called **axioms**. Without these axioms, it becomes difficult to 
infer anything with certainty. 
Axioms also make it easier to recognize when another structure satisfies 
the same axioms and therefore has all the properties that can be inferred from them.

An example could be Peano's axioms, which are a set of axioms that declare 
the properties of the natural numbers.

### Peano axioms

The **set** of natural numbers $\mathbb{N}$ are characterized by:

1. **Existence of Zero**:   $0 \in \mathbb{N}$

2. **Existence of Successor**: There exists a function $S : \mathbb{N} \rightarrow \mathbb{N}$ called the successor function..

3. **Zero has no predecessor**: $\forall n \in \mathbb{N},\quad S(n) \neq 0$

4. **The successor function is injective**:  $\forall n,m \in \mathbb{N},\quad  S(n)=S(m) \Rightarrow n=m$

5. **Principle of induction**: For every subset $A \subseteq \mathbb{N}$,
   $$0\in A \quad\land\quad
   \forall n\in\mathbb{N},\,
   (n\in A \Rightarrow S(n)\in A)
   \quad\Rightarrow\quad
   A=\mathbb{N}.$$
