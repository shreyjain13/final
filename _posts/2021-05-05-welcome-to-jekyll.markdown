---
layout: single
classes:
  - landing
  - dark-theme
toc: true
toc_sticky: true
toc_label: "Outline"
words_per_minute: 250
categories: jekyll update
author: Shrey Jain
author_profile: true
show_date: true
read_time: true

#Things you need to edit for each blog
title:  "A Primer in Domain Generalization"
date:   2021-05-05 11:38:09 -0400

---
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>

# This blog post is in the works.

Developing **robust** models that are able to **generalize** to **out-of-distribution (OOD)** data has become a popular topic for many machine learning researchers to work on in order to improve the utility of machine learning in practice.

This blog aims at providing an introduction to domain generalization work for individuals that interested in contributing to the field and understanding some of the most important open questions. I am not an expert in any of these fields and would appreciate any critique to this blog from those who are.

I have structured the blog in the following way:

* Defining the jargon
* Problem definition
* Seminal work
* Resources to get started

## Defining the jargon

In domain generalization work, there are specific words that have not been consistently defined, but for the purposes of this blog, I have defined these terms in way that I found to be most intuitive.

* Robustness
* Spurious Correlations
* Tasks

Areas of research include

* Domain generalization
* Meta learning
* Multi task learning
* Distributional robustness
* Adversarial Robustness
* Out of distribution detection
* Domain adaptation
* Zero-shot learning
* Few-shot learning
* Transfer learning

I have tried to break down the dichotomoy of what each of these are in this figure and clustered by similarity.

### Robustness

The task is defined as some probability distribution over inputs and and some loss function.  

![Relative Robustness](/assets/dgblog/relative.png)

## Problem Definition

Domain generalization, distributional robustness, adversarial robustness, out-of-distribution detection, domain adaptation, zero-shot learning, transfer learning, multi-task learning, meta-learning.

For those of you who are new to domain generalization work, I would also suggest you develop a good understanding for what a manifold is properly.
