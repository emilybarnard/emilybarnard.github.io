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
- [Presentations](#presentations)

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
    \node [above, left] at (-2,1.01) {1};
     \node [above] at (0,.85) {{2}};
      \node [above, right] at (2,1.01) {3};
      \node [above] at (-1.5,1.75) {1,2};
      \node [above] at (1.5,1.75) {2,3};
      \node [above] at (0,1.83) {1,3};
       \node[above] at (0,3) {1,2,3};
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

1. "Cambrian combinatorics on quiver representations (type A)." (with [E. Gunawan](https://egunawan.github.io/), [E. Meehan](https://wheatoncollege.edu/academics/faculty-directory/meehan-emily/), and [R. Schiffler](https://schiffler.math.uconn.edu/)) *Adv. in Appl. Math.* 143 (2023), no. 102428. [arXiv:1912.02840][].
2. "Pairwise Compatibility for 2-Simple Minded Collections II: Preprojective Algebras and Semibrick Pairs of Full Rank." (with [E.J. Hanson](https://sites.google.com/view/erichanson/home)) *Ann. Comb.* (2022). [arxiv: 2010.08645][].
3. "Dynamical combinatorics and torsion classes." (with [G. Todorov](https://gtodorov.sites.northeastern.edu/) and S. Zhu) *J. Pure and Applied Algebra*, 25 (2021), no. 9. [arxiv: 1911.10712][].
4. "Lattices from graph associahedra and subalgebras of the Malvenuto–Reutenauer algebra." (with [T. McConville](https://facultyweb.kennesaw.edu/tmcconvi/)) *Algebra universalis* 82 (2021), no. 2. [arxiv: 1808.05670][].
5. "The canonical join complex of the Tamari lattice." *J. Combinatorial Theory.* Series A (2020), 174.
6. "Lattices from graph associahedra." (with [T. McConville](https://facultyweb.kennesaw.edu/tmcconvi/)) *Sem. Lothar. Combin. proc.* **FPSAC** 2019
7. “The canonical join complex.” *Electron. J. Combin.* (2019). [arxiv: 1610.05137][].
8. “Minimal inclusions of torsion classes.” (with A. Carroll and S. Zhu.) *Algebraic Combin.* 2 (2019), no. 5, 879-901. [arxiv: 1710.08837][].
9. “The canonical join complex of the Tamari lattice.” *Sem. Lothar. Combin. proc.* **FPSAC** 2018
10. “Coxeter-biCatalan Combinatorics.” (with [N. Reading](https://nreadin.math.ncsu.edu/)) *J. Algebraic Combin.* 47 (2018), no. 2, 241–300. [arxiv: 1605.03524][].
11. “Universal geometric coefficients for the four-punctured sphere.” (with [E. Meehan](https://wheatoncollege.edu/academics/faculty-directory/meehan-emily/), [N. Reading](https://nreadin.math.ncsu.edu/), and [S. Viel](https://services.math.duke.edu/~viel/).) *Ann. Comb.* 22 (2018), no. 1, 1–44. [arxiv: 1602.03448][].
12. “Coxeter-biCatalan Combinatorics.” (with [N. Reading](https://nreadin.math.ncsu.edu/)) *DMTCS Proceedings* **FPSAC** 2015 
13. “Universal geometric coefficients for the four-punctured sphere.” (with [E. Meehan](https://wheatoncollege.edu/academics/faculty-directory/meehan-emily/), [N. Reading](https://nreadin.math.ncsu.edu/), and [S. Viel](https://services.math.duke.edu/~viel/).) *DMTCS Proceedings* **FPSAC** 2015
{: reversed="reversed"}

  [arXiv:1912.02840]: https://arxiv.org/abs/1912.02840
  [arxiv: 2010.08645]: https://arxiv.org/abs/2010.08645
  [arxiv: 1911.10712]: https://arxiv.org/abs/1911.10712
  [arxiv: 1808.05670]: https://arxiv.org/abs/1808.05670
  [arxiv: 1610.05137]: https://arxiv.org/abs/1610.05137
  [arxiv: 1710.08837]: https://arxiv.org/abs/1710.08837
  [arxiv: 1605.03524]: https://arxiv.org/abs/1605.03524
  [arxiv: 1602.03448]: https://arxiv.org/abs/1602.03448
  
## Preprints

1. "Pop-Stack Operators for Torsion Classes and Cambrian Lattices." (with [C. Defant](https://sites.google.com/view/colin-defant/home) and [E.J. Hanson](https://sites.google.com/view/erichanson/home)). Preprint [arXiv:2312.03959][].
2. "Exceptional sequences in semidistributive lattices and the poset topology of wide subcategories." (with [E.J. Hanson](https://sites.google.com/view/erichanson/home)). Preprint [arXiv:2209.11734][].
{: reversed="reversed"}

  [arXiv:2312.03959]: https://arxiv.org/abs/2312.03959
  [arXiv:2209.11734]: https://arxiv.org/abs/2209.11734

## Presentations

1. _Combinatorics of $\tau$-exceptional sequences_, University of Waterloo Combinatorics Algebraic and Enumerative Seminar --- Jan. 2023
2. _Triangulations and maximal almost rigid representations_, Special Session on Representation Theory of Algebras, CMS Winter Meeting, Toronto, Canada --- Dec. 2022
3. _New-biCambrian Lattices_, TACO Seminar, Loyola University --- Nov. 2022
4. _New-biCambrian Lattices_, Algebraic Combinatorics Seminar, Universit\`e Gustave Eiffel, Paris --- Sept. 2022
5. _Dynamics and Topology of Lattice Posets Related to the Weak Order_, Discrete Math Seminar, IIT --- Oct. 2022
6. _Kappa-Rowmotion for Semidistributive Lattices_, Dynamical Algebraic Combinatorics Workshop, UBC Okanagan, Canada --- Nov. 2021   
7. _Fundamentally Semidistributive Lattices_, UMass Lowell Math Department Colloquium (Online) --- Oct. 2021
8. _Invited Course Teacher - Tamari Lattices and Posets_, Summer School in Algebraic Combinatorics, Universit\'e du Qu\'ebec \`a Montr\'eal --- June 2021
9. _Pairwise completability for 2-Simple minded collections_, Minisymposium on Flow Polytopes of Graphs, CanaDAM 2021 --- May 2021
10. _Pairwise completability for 2-Simple minded collections_, Special Session on Algebraic and Combinatorial Aspects of Polytopes, AMS Spring Sectional Meeting, San Francisco State University --- April 2021
11. _The Kreweras Complement on the Lattice of Torsion Classes_, Dynamical Algebraic Combinatorics Virtual Workshop, BIRS, Alberta, Canada --- Oct. 2020
12. _Pairwise completability for 2-Simple minded collections_, Discrete CATS Seminar, University of Kentucky (Online) --- March 2021
13. _Cover Relations in the Lattice of Torsion Classes: Dynamics and Completability_, Online seminar on representation theory of finite-dimensional algebra --- Feb. 2021
14. _The Kreweras Complement on the Lattice of Torsion Classes_, 30th Meeting on Representation Theory of Algebras,  Universit\'e de Sherbrooke, Sherbrooke, Qu\'ebec, Canada --- Sept. 2020
15. _Graph Associahedra and the Poset of Maximal Tubings_, Combinatorics Seminar, University of Michigan, Ann Arbor, MI --- Oct. 2019
16. _Graph Associahedra and the Poset of Maximal Tubings_, Algebra and Combinatorics Seminar, Loyola University, Chicago, IL --- Sept. 2019
17. _Graph Associahedra and the Poset of Maximal Tubings_, FPSAC, University of Ljubljana, Slovenia --- July 2019
18. _Graph Associahedra and the Poset of Maximal Tubings_, CanaDAM, Vancouver, British Columbia, Canada --- May 2019
19. _Graph Associahedra and the Poset of Maximal Tubings_, Discrete Math Seminar, University of Massachusetts, Amherst, MA --- April 2019 
20. _Graph Associahedra and the Poset of Maximal Tubings_, Special Session on Cluster Algebras and Related Topics, AMS Spring Sectional Meeting, University of Connecticut, Hartford, CT --- Feb. 2019
21. _Graph Associahedra and the Poset of Maximal Tubings_, Combinatorics Seminar, Universit\'e du Qu\'ebec \`a Montr\'eal, Montr\'eal, QC --- Feb. 2019
22. _The combinatorics of torsion classes_, Special Session on Representation Theory of Algebras, CMS Summer Meeting, Fredericton, New Brunswick, Canada --- June 2018
23. _Graph Associahedra and the Poset of Maximal Tubings_, Algebra and Combinatorics Seminar, NC State University, Raleigh, NC --- May 2018
24. _The combinatorics of torsion classes_, Special Session on Noncommutative Algebra and Representation Theory, AMS Spring Sectional Meeting, Northeastern University, Boston, MA --- May 2018    
25. _Graph Associahedra and the Poset of Maximal Tubings_, Special Session on Algebraic, Geometric, and Topological Methods in Combinatorics, AMS Spring Sectional Meeting, Northeastern University, Boston, MA --- April 2018
26. _The biCatalan Kreweras Complement_, Special Session on Dynamical Algebraic Combinatorics, Joint Mathematics Meetings, San Diego, CA --- Jan. 2018
27. _The combinatorics of torsion classes_, Cluster Algebra Seminar, University of Connecticut, Storrs, CT --- Dec. 2017
28. _The combinatorics of torsion classes_, Geometry-Algebra-Singularities-Combinatorics Seminar, Northeastern University, Boston, MA --- 2017
29. _Counting and the canonical join representation_, Pick My Brain Seminar, Northeastern University, Boston, MA --- 2017
30. _The canonical join complex of the Tamari lattice_, Algebraic Combinatorixx 2 Workshop, BIRS, Alberta, Canada --- 2017
31. _Quick Fire Talk: The canonical join complex_, Connections for Women: Geometric and Topological Combinatorics, MSRI --- 2017
32. _The canonical join complex_, Combinatorics Seminar, Massachusetts Institute of Technology, Cambridge, MA --- 2017
33. _The canonical join complex_, Representation Theory Seminar, Northeastern University, Boston, MA --- 2017
34. _The canonical join complex_, Special Session Algebraic and Enumerative Combinatorics, AMS Fall Sectional Meeting, Bowdoin College, Brunswick, ME --- 2016
35. _The canonical join complex_, Maurice Auslander Distinguished Lectures and International Conference, Woods Hole Oceanographic Institution, Quissett Campus, Woods Hole, MA --- 2016
36. _Coxeter-biCatalan Combinatorics_, Combinatorics Seminar, University of Michigan, Ann Arbor, MI --- 2015
37. _Coxeter-biCatalan Combinatorics_, Combinatorics Seminar, University of Minnesota, Minneapolis, MN --- 2015
38. _Coxeter-biCatalan Combinatorics_, Algebra and Combinatorics Seminar, NC State University, Raleigh, NC --- 2015
39. _Coxeter-biCatalan Combinatorics_, Algebra and Combinatorics Seminar, DePaul University,  Chicago, IL --- 2015
40. _Coxeter-biCatalan Combinatorics_, Combinatorics Seminar, Universit\'e du Qu\'ebec \`a Montr\'eal, Montr\'eal, QC --- 2015
41. _Coxeter-biCatalan Combinatorics_, FPSAC, Korea Advanced Institute of Science and Technology, Daejeon, South Korea --- 2015
42. _Coxeter-biCatalan Combinatorics_, Special Session on Cluster Algebras, Joint Mathematics Meetings, San Antonio, TX --- 2015
{: reversed="reversed"}

