---
title: "Scalable Multi-Agent Reinforcement Learning through Intelligent Information Aggregation"
collection: toappear
permalink: /publication/informarl
date: 2022-10-26
venue: 'Under Review'
---
Authors: **Siddharth Nayak**, Kenneth Choi, Wenqi Ding, Sydney Dolan, Karthik Gopalakrishnan, Hamsa Balakrishnan

We consider the problem of multi-agent navigation and collision avoidance when observations are limited to the local neighborhood of each agent. We propose InforMARL, a novel architecture for multi-agent reinforcement learning (MARL) which uses local information intelligently to compute paths for all the agents in a decentralized manner. Specifically, InforMARL aggregates information about the local neighborhood of agents for both the actor and the critic using a graph neural network and can be used in conjunction with any standard MARL algorithm. We show that (1) in training, InforMARL has better sample efficiency and performance than baseline approaches, despite using less information, and (2) in testing, it scales well to environments with arbitrary numbers of agents and obstacles. [[PDF]](https://arxiv.org/abs/2211.02127), [[Code]](https://github.com/nsidn98/InforMARL), [[Project Website]](https://nsidn98.github.io/InforMARL/)

Note: Code will be made public soon.

<!-- Recommended citation: Your Namesdas, You. (2010). "Paper Title Number 2." <i>Journal 1</i>. 1(2). -->
