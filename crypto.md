---

layout: single
classes:
  - landing
  - dark-theme
title:  "CS 330 Notes"
toc: true
toc_sticky: true
toc_label: "Course Lectures"
table_icon: "address-book"

categories: jekyll update
author: Shrey Jain
author_profile: true
show_date: false
permalink: /crypto/
---
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>

This blog is aimed at giving a condensed explanation of the science behind cryptocurriences. Specififcally, this blog will be aimed at explaning the basics behind Bitcoin but should be generalizeable to different types of *alt* coins.

# Cryptographic Hash Functions

## Property 1: Collision-Free Hash Functions

The goal of a collision free hash function is to say that nobody can find an $$x$$ and a $$y$$ such that $$x!=y$$ and $$H(x)= H(y)$$. If $$H(x) = H(y)$$, it is fair to assume that $$x =y$$.

## Property 2: Hiding

Hiding is trying to say that if I sample an $$r$$ from a probbility distribution of a high min-entropy and I can compute the hash function of $$r$$ together with $$x$$, then it is infeasible to compute $$x$$.

**High min-entropy** means that the distribution is "very spread out", so that no particular value is chosen with more than neglible property.

A more intuitive way to think about this is to think that if $$r$$ is chosen uniformly from all of the strings that are 256 bits long than any particular string was chosen in $$\frac{1}{2^{256}}%$$ which is a neglible value.

**Application of Hiding**: Commitmment


![Commitment](/assets/cryptocourse/commitment.png)
