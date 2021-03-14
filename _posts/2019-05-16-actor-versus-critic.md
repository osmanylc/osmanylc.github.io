---
title: Actor Versus Critic
layout: post
date: 2019-05-16 00:00
tag: reinforcement-learning
projects: true
category: projects
author: osmany
---

<div style="text-align:center">
<img alt="Frame of pong game played by reinforcement learning agent." src="{{ site.url }}/assets/images/pong_frame.png" width="75%" />
</div>

:link: Project Link: [DQN Agent](https://github.com/osmanylc/dqn-implementation)

:book: Project Writeup: [Actor Versus Critic]({{ site.url }}/assets/documents/actor_versus_critic_report.pdf)

This project compares the performance of value function approximation and policy optimization methods for solving reinforcement learning problems. The Deep Q-Network (DQN) architecture was chosen as a representative of a value function approximation method, and Proximal Policy Optimization (PPO) as a policy optimization method. I implemented the DQN architecture and used OpenAI’s baseline implementations of DQN and PPO to learn evaluate the algorithms on Atari 2600 Pong from OpenAI Gym. The vanilla DQN architecture was not able to learn a successful policy, so an implementation of DQN with prioritized experience replay was used for comparison with PPO. In the experiments, the DQN player learns a successful policy much more quickly than the PPO player and also with less variance, thus DQN seems to be a better algorithm for the game of Pong.
