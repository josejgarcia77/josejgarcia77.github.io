---
layout: page
title: Structure Preserving Curvature-Guided Graph Sparsification
description: A study of curvature-guided methods for sparcifying graphs whiel maintainging community structure with an eye towards computational improvements.
img: assets/img/curvature.png
importance: 1
category: graduate
related_publications: false
---

Authors: Avin Kolahdooz, José Jairo García, and Sarah Percival

My role: Co-author (second author), mainly support with codebase and verification.

Large networks can be difficult to analyze efficiently while preserving their community structure. In this project, we study a two-stage graph-sparsification pipeline that first uses the computationally inexpensive Lower Ricci Curvature (LRC) to filter edges, then refines the reduced graph using Ollivier-Ricci curvature (ORC) and Ricci flow. We evaluate the approach on synthetic and real-world networks, comparing community-recovery accuracy with runtime. The combined method achieves competitive accuracy on selected networks and reduces computation on most evaluated benchmarks, though its effectiveness depends on the structure of each network.

Research paper in the works.