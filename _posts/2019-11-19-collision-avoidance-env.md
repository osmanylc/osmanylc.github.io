---
title: Collision Avoidance Environment
layout: post
date: 2019-11-19 00:00
tag: reinforcement-learning
projects: true
hidden: true
category: project
author: osmany
---

## Project Link: [Deep RL Collision Avoidance](https://github.com/osmanylc/deep-rl-collision-avoidance)
## Project Report: [project_report.pdf]({{ site.url }}/assets/documents/collision_avoidance_env_report.pdf)

![Sample encounter path]({{ site.url }}/assets/images/encounter_path.png)

An environment for simulating encounters between aircraft for the purpose of creating collision avoidance systems. It is compatible with the collection of deep reinforcement learning models made available by OpenAI's baselines repo.

We experiment with different parameters for define the encounter environment. For example, we change how an intruder aircraft behaves, having it turn randomly at every time step or sustaining a maneuver for a period of time. We find that the collision avoidance policies learned by the aircraft adapt to the intruder's behavior, giving us a way to trade off efficiency vs. safety in a policy.
