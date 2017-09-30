---
layout: post
mathjax: true
title: Hyperoperators - A Journey into Forbidden Math
---

What's the biggest number you've ever tried to imagine? Ever wonder whether functions exist that grow much faster than the exponential or
factorial? Both these notations are capable of representing huge numbers that are large enough for any real application. For example there are roughly $$10^{86}$$ elementary particles in the visible universe and $$8\cdot2^{10^{12}}$$ possible configurations in a 1 TB solid state drive. However one can still imagine plenty of numbers far larger than this, but with seemingly no way to express them.  
Recently, I came across the [wikipedia page for hyperoperators](https://en.wikipedia.org/wiki/Hyperoperation). The basic idea is that the sequence of operations-- addition, multiplication, and exponentiation each seem to build on each other in a way that can naturally be extended to an infinite series of operations.  
Suppose we have the hyperoperator function that takes arguements:  

$$h(n,a,b)\,|\, n, a, b \in \mathbb{Z}^{+}$$
  
Where $$n$$ specifies the particular operator from the series that will be applied to $$a$$ and $$b$$.  
For example, $$h(1,a,b)$$ simply represents the addition of $$a$$ and $$b$$. 
This is equalivilent to repeated incrementing of $$a$$, $$b$$ times.  

$$h(1,a,b) = a + b = a+\underbrace{1+1+\ldots+1}_\text{b}$$  
  
$$h(2,a,b)$$ multiplies $$a$$ and $$b$$. This equivilent to repeated addition.  
  
$$h(2,a,b) = a \cdot b = \underbrace{a+a+\ldots+a}_\text{b}$$  
  
$$h(3,a,b)$$ is the exponentiation $$a$$ raised to the $$b$$. This is equivilent to repeated multiplication.  
  
$$h(3,a,b) = a^b = \underbrace{a\cdot a \cdot \ldots \cdot a}_\text{b}$$  
  
$$h(4,a,b)$$ is called tetration, and is equivilent to a stack of exponents with a height of $$b$$.  
  
$$h(4,a,b) = b\begin{cases}a^{\,a^{\,\ldots^{\,a}}}\end{cases}$$
  
See the pattern? Continuing, $$h(n,a,b)$$ applies the $$nth$$ hyperoperator to $$a$$ and $$b$$ by repeatedly using $$h(n-1, \ldots)$$. We now have a function that grows fast. In fact, if one wanted to write down just $$h(10,10,10)$$ in stacked exponential notation, you could convert all of the universe's mass into sheets of paper, fill every page with writing and still make effectively no progress towards writing that number down. It's rather surprising that the first few operations in this little-known series just happen to be essential building blocks of mathematics, but when $$n>3$$ for whatever reason they become virtually useless. Why is this? Something is wrong. 