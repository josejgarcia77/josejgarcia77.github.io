---
layout: page
title: Stirling Numbers of Sunflower Graphs
description: Combinatorics of a special type of graph, relation to graph colorings, and recursion.
img:
importance: 1
category: work
related_publications: false
---

Advisor: Dr. Lauren Keough

Contributors: José J. Garcia, Jessica Longo, Matt Phad, Page Wilson

A Stirling number of the second kind, $S(n,k)$, is the number of ways to take all of the elements from an $n$ element set and put them into $k$ subsets, so that the subsets are non-empty and pairwise disjoint. To get the graphical Stirling number for a graph $G$, we add the restriction that any two vertices that are adjacent in $G$ cannot be in the same subset. The traditional Stirling numbers are the graphical Stirling number where the graph is empty. We find graphical Stirling numbers for sunflower graphs, which are powers of paths joined at a single vertex. We approach the problem in two different ways, (1) by finding the chromatic polynomial and (2) recursively. Our results include the Stirling number for what we refer to as a complete sunflower graph, as well as a few other cases for sunflower graphs. We then form a general conjecture for the chromatic polynomial of a sunflower graph, which would then provide us with the graphical Stirling number for a sunflower graph using the Principle of Inclusion Exclusion.
We also find several recursive formulas for finding graphical Stirling numbers, such as the graphical Stirling number for graph $G$ with vertex $v$ with a complete neighborhood, $S(G,k)=S(G-v,k-1)+(k-\text{deg}(v))\cdot S(G-v,k).$ We end with a discussion of possible future work.
