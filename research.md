---
layout: page
title: Research
permalink: /research/
---

I am an algebraic combinatorialist, which means I organize discrete data in ways that highlight useful structures or patterns. Most often the "data" I consider consists of a family of objects that appear in vastly disconnected fields of mathematics or physics. My research begins with two superficially simple questions:
- In each family, how many objects are there?
- In each family, are some objects bigger than others?

The type of answer we expect from the first question is straightforward. No matter how complicated the objects we are counting, we expect that the number of objects is a non-negative whole number. Since we typically consider an infinite family of objects, the solution to our counting problem is an infinite sequence of such numbers. The Fibonacci numbers or the binomial coefficients are famous examples of such sequences of numbers.

The type of answer we expect from the second question is a little more complicated, but roughly we would like a *rule* which tells us when and how to compare different objects. It is possible that some of our objects may not be comparable at all. For this reason, we say that a set of objects together with a rule $(\le)$ that compares some of the objects is a *partially ordered set*, or a *poset* for short.

<script type="text/tikz">
\begin{tikzpicture}
 %\draw[help lines] (-3,-3) grid (5,5);
 \node [below] at (0,0) {Empty Set};
  \node [above, left] at (-2,1.01) {$\{1\}$};
   \node [above] at (0,.85) {$\{2\}$};
    \node [above, right] at (2,1.01) {$\{3\}$};
    \node [above] at (-1.5,1.75) {$\{1,2\}$};
    \node [above] at (1.5,1.75) {$\{2,3\}$};
    \node [above] at (0,1.83) {$\{1,3\}$};
     \node[above] at (0,3) {$\{1,2,3\}$};
     \node[above] at (0,-2) {Figure 1. A poset.};
\draw (0,0) --(-2,1);
\draw (0,0) --(2,1);
\draw (0,0) --(0,.9);
\draw (-2,1) -- (-1.5,1.8);
\draw (-.25,.95) -- (-1.5, 1.8);
\draw (0.25,.95) -- (1.5, 1.8);
\draw (2,1) -- (1.5, 1.8);
\draw(-2,1) -- (0,1.85);
\draw(2,1) -- (0, 1.85);
\draw(0,3) -- (0, 2.5);
\draw(-1,2.3) -- (0, 3);
\draw(1,2.3) -- (0,3);
\end{tikzpicture}
</script>

The figure above shows a picture of the poset of subsets of the set $\{1,2,3\}$. A set $A$ is "bigger" than a set $B$ if all of the elements of $A$ are also in $B$.

I am particularly interested in posets that come "from nature." For me, a poset is "from nature" if it grows from the study of some mathematical object, be it a polytope or a category of modules. A poset "from nature" could be a poset whose Hasse diagram (or underlying graph) is the one-skeleton of a polytope; or a poset whose elements are collections of certain subcategories. My research program leverages the geometric and algebraic structure of such posets to answer combinatorial questions.

## Publications

{% include_relative _includes/publications.md %}
