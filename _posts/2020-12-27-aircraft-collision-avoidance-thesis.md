---
title: Aircraft Collision Avoidance Thesis
layout: post
date: 2020-05-18 00:00
tag: reinforcement-learning
projects: true
hidden: true
category: project
author: osmany
---

![Policy plot]({{ site.url }}/assets/images/policy_plot.png)

## Abstract

Current airborne collision avoidance systems are limited in the number of variables they can use to describe an encounter between aircraft. The solution method currently used, dynamic programming (DP), requires the discretization of continuous variables and a split between the set of horizontal and vertical variables. These approximations limit how extensible the system is to new environments, and can negatively impact its performance. In this work, we present a method to build a collision avoidance logic with DP that uses all the variables in a three-dimensional encounter for the purpose of evaluating its performance. We do this by limiting the values that some variables can take, and building small tables that can be evaluated on partitions of a large encounter set. The 3D logic is able to achieve similar performance to ACAS X while using a simpler model. To exploit the benefits of the fully 3D logic approach without the computational limitations, we build a simulation environment and implement a deep reinforcement learning algorithm that can learn successful collision avoidance logics consistently. Our experiments show that this approach can learn logics using models of the problem that would be impractical for a DP solution to solve.

Link to full text: [https://hdl.handle.net/1721.1/127392](https://hdl.handle.net/1721.1/127392)
