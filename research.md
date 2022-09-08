---
layout: page
title: Research
permalink: /research/
---

Skip to...
- [Research Interests](#research-interests)
- [Research Narrative](#research-narrative)
- [Publications and Peer Reviewed Conference Proceedings](#publications-and-peer-reviewed-conference-proceedings)
- [Preprints](#preprints)

## Research Interests

Algebraic combinatorics, particularly lattice theory in connection with Coxeter groups and representation theory.

## Research Narrative

I am an algebraic combinatorialist, which means I organize discrete data in ways that highlight useful structures or patterns. Most often the "data" I consider consists of a family of objects that appear in vastly disconnected fields of mathematics or physics. My research begins with two superficially simple questions:
- In each family, how many objects are there?
- In each family, are some objects bigger than others?

The type of answer we expect from the first question is straightforward. No matter how complicated the objects we are counting, we expect that the number of objects is a non-negative whole number. Since we typically consider an infinite family of objects, the solution to our counting problem is an infinite sequence of such numbers. The Fibonacci numbers or the binomial coefficients are famous examples of such sequences of numbers.

The type of answer we expect from the second question is a little more complicated, but roughly we would like a *rule* which tells us when and how to compare different objects. It is possible that some of our objects may not be comparable at all. For this reason, we say that a set of objects together with a rule $(\le)$ that compares some of the objects is a *partially ordered set*, or a *poset* for short.

<div class="right">
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
</div>
Figure 1 shows a picture of the poset of subsets of the set $\{1,2,3\}$. A set $A$ is "bigger" than a set $B$ if all of the elements of $A$ are also in $B$.

I am particularly interested in posets that come "from nature." For me, a poset is "from nature" if it grows from the study of some mathematical object, be it a polytope or a category of modules. A poset "from nature" could be a poset whose Hasse diagram (or underlying graph) is the one-skeleton of a polytope; or a poset whose elements are collections of certain subcategories. My research program leverages the geometric and algebraic structure of such posets to answer combinatorial questions.

<!-- Publications -->
## Publications and Peer Reviewed Conference Proceedings
You can also find my publications on the [arXiv](https://arxiv.org/search/math?searchtype=author&query=Barnard%2C+E) and [Google Scholar](https://scholar.google.com/citations?user=Lr5Hl80AAAAJ).

<!-- 
Convert your LaTeX publications list from LaTeX to Markdown syntax: https://pandoc.org/try/?text=&from=latex&to=gfm
Paste the generated Markdown below, and edit as needed.
Or, just add your publications using Markdown syntax below.
-->

12. "Pairwise Compatibility for 2-Simple Minded Collections II: Preprojective Algebras and Semibrick Pairs of Full Rank." (with E.J. Hanson) *Ann. Comb.* (2022). [arxiv: 2010.08645][].
11. "Dynamical combinatorics and torsion classes." (with G. Todorov and S. Zhu) *J. Pure and Applied Algebra*, 25 (2021), no. 9. [arxiv: 1911.10712][].
10. "Lattices from graph associahedra and subalgebras of the Malvenuto–Reutenauer algebra." (with T. McConville) *Algebra universalis* 82 (2021), no. 2. [arxiv: 1808.05670][].
9. "The canonical join complex of the Tamari lattice." *J. Combinatorial Theory.* Series A (2020), 174.
8. "Lattices from graph associahedra." (with T. McConville) *Sem. Lothar. Combin. proc.* **FPSAC** 2019
7. “The canonical join complex.” *Electron. J. Combin.* (2019). [arxiv: 1610.05137][].
6. “Minimal inclusions of torsion classes.” (with A. Carroll and S. Zhu.) *Algebraic Combin.* 2 (2019), no. 5, 879-901. [arxiv: 1710.08837][].
5. “The canonical join complex of the Tamari lattice.” *Sem. Lothar. Combin. proc.* **FPSAC** 2018
4. “Coxeter-biCatalan Combinatorics.” (with N. Reading) *J. Algebraic Combin.* 47 (2018), no. 2, 241–300. [arxiv: 1605.03524][].
3. “Universal geometric coefficients for the four-punctured sphere.” (with E. Meehan, N. Reading, and S. Viel.) *Ann. Comb.* 22 (2018), no. 1, 1–44. [arxiv: 1602.03448][].
2. “Coxeter-biCatalan Combinatorics.” (with N. Reading) *DMTCS Proceedings* **FPSAC** 2015 
1. “Universal geometric coefficients for the four-punctured sphere.” (with E. Meehan, N. Reading, and S. Viel.) *DMTCS Proceedings* **FPSAC** 2015
{: reversed="reversed"}

  [arxiv: 2010.08645]: https://arxiv.org/abs/2010.08645
  [arxiv: 1911.10712]: https://arxiv.org/abs/1911.10712
  [arxiv: 1808.05670]: https://arxiv.org/abs/1808.05670
  [arxiv: 1610.05137]: https://arxiv.org/abs/1610.05137
  [arxiv: 1710.08837]: https://arxiv.org/abs/1710.08837
  [arxiv: 1605.03524]: https://arxiv.org/abs/1605.03524
  [arxiv: 1602.03448]: https://arxiv.org/abs/1602.03448
  
## Preprints

1. "Cambrian combinatorics on quiver representations (type A)." (with E. Gunawan, E. Meehan, and R. Schiffler). Preprint [arXiv:1912.02840][].
{: reversed="reversed"}

  [arXiv:1912.02840]: https://arxiv.org/abs/1912.02840
