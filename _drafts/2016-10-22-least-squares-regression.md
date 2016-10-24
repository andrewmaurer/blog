---
layout: single
title: Least squares regression for mathematicians
category: statistical-learning
tags: [linear-regression,statistics,least-squares,machine-learning,statistical-learning]
date: 2016-10-22 02:02:00
---

Suppose you have some relationship $$\{x_i \mapsto y_i\}_{i=1}^n$$, where $$x_i \in V$$, a real normed vector space, and $$y_i \in W$$, another real normed vector space. We would like to find an affine transformation that, with respect to our data, best approximates the mapping $$x_i \to y_i$$.

If $$f:V \to W$$ is any function, the goal is to find the following:

  * A notion of *individualized error* $$E(f(x_i),y_i)$$. This will generally be $$W$$'s norm.
  * A notion of *total error* $$E_\Sigma(\{f(x_i)\},\{y_i\})$$. In this case we take 

    $$E_\Sigma(\{f(x_i\},\{y_i\}) = \sum_i E(x_i,y_i)^2$$
  
