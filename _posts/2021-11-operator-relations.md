---
title: 'Operator Relations'
date: 2020-11-14
permalink: /posts/2020/11/operator-relations/
tags:
  - math tricks
---


Let 

$$
f(\lambda)=\text{e}^{\lambda A}B\text{e}^{-\lambda A}
$$

then, one can expand $f$ in Taylor series about the origin. We first evaluate the derivatives

$$
\frac{\mathrm{d}f}{\mathrm{d}\lambda}=\text{e}^{\lambda A} [A, B] \text{e}^{-\lambda A}
$$

so

$$
f'(0)=[A,B]
$$

Similarly

$$
\frac{\mathrm{d}^2f}{\mathrm{d}\lambda^2}=\text{e}^{\lambda A} [A, [A, B]] \text{e}^{-\lambda A}
$$

so that

$$
f''(0)=[A,[A,B]]
$$

Now, we write the Taylor’s expansion

$$
f(\lambda)=f(0)+\lambda f'(0) + \frac{\lambda^2}{n!}f''(0)+\cdots
$$

or

$$
\text{e}^{\lambda A}B\text{e}^{-\lambda A}=B+\lambda[A,B]+\frac{\lambda^2}{2!}[A,[A,B]]+\cdots
$$

A particular case is when $[A, B] = c$, where $c$ is a c-number, then

$$
\text{e}^{\lambda A}B\text{e}^{-\lambda A}=B+\lambda c
$$

in which case exp(αA) acts as a displacement operator.
