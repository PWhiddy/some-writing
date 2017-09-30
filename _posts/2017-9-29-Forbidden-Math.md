---
layout: post
mathjax: true
title: Hyperoperators - A Journey into Forbidden Math
---

Ever wonder whether functions exist that grow much faster than the exponential or
factorial? While both these notations are capable of representing huge numbers large enough for any real application, there are still plenty of bigger numbers out there with seemingly no way to get at them.  
Recently, I came across the [wikipedia page for hyperoperators](https://en.wikipedia.org/wiki/Hyperoperation). The basic idea is that the sequence of operations-- addition, multiplication, and exponentiation seem to build on each other in a way follow a pattern that could naturally be extended to an infinite series of operations.  
Suppose we have the hyperoperator function that takes arguements:  

$$h (n,a,b)\,|\, n, a, b \in \mathbb{Z}^{+}$$
  
Where $$n$$ specifies the particular operator from the series that will be applied to $$a$$ and $$b$$.  
For example, $$h(1,a,b)$$ simply represents the addition of $$a$$ and $$b$$. 
This is equalivilent to repeated incrementing of $$a$$, $$b$$ times.  

$$a+\underbrace{1+1+\ldots+1}_\text{b}$$  
  
$$h(2,a,b)$$ multiplies $$a$$ and $$b$$. This equivilent to repeated addition.  
  
$$\underbrace{a+a+\ldots+a}_\text{b}$$  
  
$$h(3,a,b)$$ is the exponentiation $$a$$ raised to the $$b$$. This is equivilent to repeated multiplication.  
  
$$\underbrace{a\dot a \dot ldots \dot a}_\text{b}$$  

The first few operations in this series just happen to be the essential building blocks of numerical mathematics, and the rest for whatever reason are nearly unheard of. 