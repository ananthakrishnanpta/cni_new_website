---
layout: page
title: FedOpt++ - Federation Beyond Uniform Client Selection, Optimization Beyond Simple Minimization
speaker: Dr. Pranay Sharma, Research Scientist, CMU
description: 
img:
importance: 1
date: 2023-03-28 16:59:00
category: ""
zoom_link: https://zoom.us/j/99506912102?pwd=c3VWNHpJdmZVWXNsNDRxdHhVaTBuZz09

recorded_video: e75_Fc6G48Q
---
**About the Speaker** 

**Pranay Sharma** is a research scientist in the Department of Electrical and Computer Engineering (ECE) at Carnegie Mellon University. Pranay finished his Ph.D. in ECE from Syracuse University in 2021, where he worked on distributed localization and target tracking, as well as distributed optimization. Before that, he finished his B.Tech-M.Tech dual degree in Electrical Engineering from IIT Kanpur in 2013. His current research focuses broadly on distributed machine learning and optimization. Specifically, his work focuses on Federated Learning, minimax optimization, differential privacy, and reinforcement learning.

**Abstract**

Large-scale edge-based collection of training data in many machine learning (ML) applications calls for communication-efficient distributed optimization algorithms, such as those used in federated learning (FL), to process the data. Our work addresses some limitations in the current FL literature. First, previous analyses of FedAvg (the most commonly used FL algorithm) assume either full participation of clients or partial participation with a uniform sampling of clients. However, in practical FL systems, client availability often follows a natural cyclic pattern. We provide (to our knowledge) the first theoretical framework to analyze the convergence of FedAvg with cyclic client participation. Another limitation of FL is the paucity of work on problems beyond simple minimization settings. Minimax optimization can model several ML applications such as GANs, multi-agent games, and reinforcement learning. Stochastic gradient descent ascent (SGDA) is one of the most common algorithms for minimax optimization. However, its convergence is not well understood in nonconvex settings. We analyze SGDA (and its variants) for several classes of nonconvex-concave and nonconvex-nonconcave minimax problems. Further, we provide novel and tighter analysis of SGDA-like methods in the federated setting, in the process improving existing convergence and communication guarantees.

