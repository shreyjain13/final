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

## Why should you care about Domain Generalization (DG)?

Developing **robust** models that are able to **generalize** to **out-of-distribution (OOD)** data has become a popular topic for many machine learning researchers to work on in order to improve the generalizeability of applied machine learning.

This blog aims at providing an introduction to domain generalization by:

* Defining the jargon
* Providing a clear explanation on the problem setting
* Highlighting seminal work and important domain generalization methods
* Provide up to date resources (talks/papers/codebases)

## Defining the jargon

In domain generalization work, as well as in machine learning more broadly, there are specific words that have not been consistently defined. In this blog I have tried to provide the most intuitive explanation of terms that I believe are being used in a hand wavy way and I have vetted my definitions by experts in this work.

Here are a list of terms I plan to clarify:

* Robustness
* Spurious Correlations
* Tasks

Make a clear distinction between the following work (ie. definition and maybe a seminal paper in that field and relevent resource)

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
* Negative Transfer Learning

### Relative Robustness

THIS IS AN EXAMPLE ON HOW I WANT TO DEFINE SOME OF THE TERMINOLOGY THAT IS COMMONLY USED.

**Whose model is more robust?**

![Relative Robustness](/assets/dgblog/rel1.png)

Now that we have the data, let's just be clear on the distributions:

![Relative Robustness](/assets/dgblog/rel2.png)

So who was right?

**Your model is more robust!**  Although I achieved higher accuracy on the data with a distribution shift, my model saw a 16% drop in performance whereas yours only saw an 8% drop. **The lower the drop in performance between distributions, the more robust a model is.**


# Introduction

### ICP (Invariant Causal Prediction) for Nonlinear models


### Generalizing from Several Related Classification Tasks to a New Unlabeled Sample

[Paper Link](https://proceedings.neurips.cc/paper/2011/file/b571ecea16a9824023ee1af16897a582-Paper.pdf)

Initial Notes:



### Causal Inference Using Invariant Prediction: Indentification and Confidence Intervals

Mathematical formulation of the problem

Visual intuitive and laymen explanation of the problem

# Seminal Work and DG Methods

### ICP and Non-Linear ICP

### Invariant Risk Minimization (IRM) & IRMV2

Discuss limitations and method formulation and maybe relevant papers for each of these

### Robust Optimization Methods

### DG & Algorithmic Fairness

### DG for Decomposition

### DG for Meta Learning

### Self-supervised Contrastive Regularization (SelfReg)

### DG Benchmarks

Probably talk about WILDS here and a lot of Pearcy Liang's work

### DG and Causal Inference

### DG Gradient Alignment

### DG Theory on Sample Complexity & PAC Learning

### Model-based DG

### DG for Computer Vision and Data Augmentation


## Resources to get started

If you are interested in getting involved in domain generalization work, I would recommend first cleaning up your understanding on causal inference and distributionally robust optimization. For lack a better word, these can be considered your "pre-requisities".

### Causal Inference

**General causal inference content**

**Papers to motivate causal inference in domain generalization**

* Here is a great list of paper

### Distributionally Robust Optimization

**General causal inference content**

### Great researchers to follow on Twitter

List a good list of people doing DG work like Chealsea Finn or Piearcy Liang
