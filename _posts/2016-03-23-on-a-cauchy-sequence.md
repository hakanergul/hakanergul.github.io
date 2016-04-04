---
title: On a Cauchy Sequence
updated: 2016-03-23 16:02
---


**Theorem:** Let $$(X,d)$$ be a metric space, $$F:X\to X$$ be a function such that for each $$\varepsilon>0$$, $$F[B(x,\varepsilon)] \subset B(x,\varepsilon)]$$. If  $$d(x_n,x_{n+1})\to 0$$, then $$\{x_n\}$$ is a Cauchy sequence.


*Proof.*
Let define $$x_n=F^n(x_0)=F(x_{n-1})$$ and $$\varepsilon>0$$, then there exists an $$N\in \mathbb{N}$$ such that for all $$k\geq N$$ we have $$d(x_k,x_{k+1})<\varepsilon$$. If $$x_N\in B(x_N,\varepsilon)$$, then $$F(x_N)=x_{N+1}\in B(x_N,\varepsilon)$$. And inductively we have for all $$k\geq 0 $$, $$ F^k(x_{N})=x_{N+k}\in B(x_N,\varepsilon) $$. Hence for all $$m,n\geq N$$ $$d(x_{m},x_n)\leq d(x_m,x_N)+d(x_N,x_n)\leq 2 \varepsilon$$, wihch is complete proof.

to be fixed...
