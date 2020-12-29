---
layout: page
title: Research
permalink: /research/
---

## Research Interests

Algebraic combinatorics, particularly lattice theory in connection with Coxeter groups and representation theory.

## Summary for a General Audience

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

## Publications

<div class="right feature">
 <ul class="profiles-links">
   {% if site.footer-links.arxiv %}
   <li>
     <a href="https://arxiv.org/search/{{ site.footer-links.arxiv }}">
       <svg aria-hidden="true" class="svg-icon arxiv" xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 100 100">
         <g>
           <rect x="31.436" y="25.673" width="37.764" height="2.178"></rect>
           <rect x="31.436" y="33.661" width="37.764" height="2.179"></rect>
           <rect x="31.436" y="42.375" width="37.764" height="2.179"></rect>
           <rect x="31.436" y="50.363" width="37.764" height="2.179"></rect>
           <rect x="31.436" y="59.077" width="37.764" height="2.179"></rect>
           <path d="M76.823,8.79H24.538c-3.604,0-6.536,2.932-6.536,6.536v69.349c0,3.604,2.932,6.536,6.536,6.536h42.119   c9.21,0,16.702-7.492,16.702-16.702V15.326C83.359,11.721,80.427,8.79,76.823,8.79z M22.358,84.675V15.326   c0-1.202,0.979-2.179,2.18-2.179h52.285c1.2,0,2.178,0.977,2.178,2.179v56.096H62.663v15.432H24.538   C23.337,86.854,22.358,85.876,22.358,84.675z M67.02,86.835V75.779h11.916C78.311,81.873,73.23,86.652,67.02,86.835z"></path>
         </g>
       </svg>
       <span class="profile-link-text">arXiv</span>
     </a>
   </li>
 {% endif %}

 {% if site.footer-links.googlescholar %}
   <li>
     <a href="https://scholar.google.com/citations?user={{ site.footer-links.googlescholar }}">
       <svg aria-hidden="true" class="svg-icon googlescholar" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
         <path d="M10.516 4.04c-.47.315-2.766 1.839-5.102 3.39-2.336 1.55-4.246 2.832-4.246 2.847 0 .016.117.094.262.172.144.082 2.449 1.36 5.125 2.844l4.86 2.7.124-.063c.07-.035 1.863-1.059 3.988-2.27l3.86-2.207.023 6.828h2.293V10.29L18.73 8.297c-4.007-2.684-7.21-4.8-7.289-4.817-.039-.007-.453.247-.925.56m-4.79 12.534l.012 1.723 2.844 1.707 2.844 1.703 2.867-1.719 2.863-1.722v-1.703c0-.938-.011-1.704-.023-1.704s-1.133.672-2.492 1.496c-1.36.82-2.641 1.594-2.84 1.715l-.371.22-1.133-.68a519.046 519.046 0 0 1-2.824-1.7c-.93-.562-1.707-1.031-1.723-1.039-.02-.008-.027.758-.023 1.703"/>
       </svg>
       <span class="profile-link-text">Google Scholar</span>
     </a>
   </li>
 {% endif %} 
 </ul>
</div>

{% include_relative _includes/publications.md %}
