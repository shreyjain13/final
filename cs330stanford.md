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
permalink: /cs3330/
---
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>
# Lecture 1

* How can we enable agents to learn skills in the real world? *Robots can teach us about intelligence*. Robots also have to be able to generalize across tasks, objects, environments and need some common sense understanding to do well.


**Specialists** is people who learn in a very specific environment and **generalists** learn very simple things to generalize a method to learn how to perform more complex tasks.

**What is a task?**

Takes an input dataset and a loss function and gives a model. A task is a machine learning problem. Different tasks can vary based on:
* differnt objects
* different people
* different objectives
* so many different things

**Crtical Assumption** is that different tasks need to share some type of structure.

### Mutli-task learning problem

Learn all of the tasks more quickly or more proficiently than learning them independently.

### Meta-Learning Problem

Given data / experience on previous asks, learn a new task more quickly and/or more proficiently
