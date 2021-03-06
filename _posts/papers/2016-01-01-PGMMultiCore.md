---
layout: external
title: Probabilistic graphical models on multi-core CPUs using Java 8
role: Experiments
category: papers
external_url: 
tags: [sade, rnb, smooth]
image:
  thumb: pgmmulticorelogo.png
published: true
---

In this paper, we discuss software design issues related to the development of parallel computational intelligence algorithms on multi-core CPUs, using the new Java 8 functional programming features. In particular, we focus on probabilistic graphical models (PGMs) and present the parallelization of a collection of algorithms that deal with inference and learning of PGMs from data. Namely, maximum likelihood estimation, importance sampling, and greedy search for solving combinatorial optimization problems. Through these concrete examples, we tackle the problem of defining efficient data structures for PGMs and parallel processing of same-size batches of data sets using Java 8 features. We also provide straightforward techniques to code parallel algorithms that seamlessly exploit multicore processors. The experimental analysis, carried out using our open source AMIDST (Analysis of MassIve Data STreams) Java toolbox, shows the merits of the proposed solutions.

Masegosa, A. R., Martinez, A. M., & Borchani, H. (2016). Probabilistic graphical models on multi-core CPUs using Java 8.
IEEE Computational Intelligence Magazine, 11(2), 41-54.

[{% icon fa-file-pdf-o %} PDF](https://ieeexplore.ieee.org/abstract/document/7450294/) [{% icon fa-github %} Github](https://github.com/amidst/toolbox) [{% icon fa-institution %} arXiv](https://arxiv.org/pdf/1604.07990)
