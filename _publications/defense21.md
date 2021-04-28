---
title: "Scalable Learning in Distributed Robot Teams"
collection: publications
permalink: /publication/2021-defense
excerpt: '<a href="https://katetolstaya.github.io/files/thesis.pdf"> [Dissertation] </a> <a href="https://youtu.be/6TdE42DG47c"> [Talk Video] </a> <a href="http://katetolstaya.github.io/files/defense.pdf"> [Slides] </a>  <a href="https://events.seas.upenn.edu/event/ese-thesis-defense-scalable-learning-in-distributed-robot-teams/"> [Additional Info] </a> '
date: 2021-4-21
venue: 'Doctoral Dissertation, University of Pennsylvania'
---

<a href="https://katetolstaya.github.io/files/thesis.pdf"> [Dissertation] </a> <a href="https://youtu.be/6TdE42DG47c"> [Talk Video] </a> <a href="http://katetolstaya.github.io/files/defense.pdf"> [Slides] </a>  <a href="https://events.seas.upenn.edu/event/ese-thesis-defense-scalable-learning-in-distributed-robot-teams/"> [Additional Info] </a> 

Mobile robots are already in use for mapping, agriculture, entertainment, and the delivery of goods and people. As robotic systems continue to become more affordable, large numbers of mobile robots may be deployed concurrently to accomplish tasks faster and more efficiently. Practical deployments of very large teams will require scalable algorithms to enable the distributed cooperation of autonomous agents. This thesis focuses on the three main algorithmic obstacles to the scalability of robot teams: coordination, control, and communication. To address these challenges, we design graph-based abstractions that allow us to apply Graph Neural Networks (GNNs).

First, a team of robots must continually coordinate to divide up mission requirements among all agents. We focus on the case studies of exploration and coverage to develop a spatial GNN controller that can coordinate a team of dozens of agents as they visit thousands of landmarks. A routing problem of this size is intractable for existing optimization-based approaches.
Second, a robot in a team must be able to execute the trajectory that will accomplish its given sub-task. In large teams with high densities of robots, planning and execution of safe, collision-free trajectories requires the joint optimization over all agent trajectories, which may be impractical in large teams. We present two approaches to scalable control: a) a controller for flocking that uses delayed communication formalized via a GNN; and b) an inverse optimal planning method that learns from real air traffic data.
Third, robot teams may need to operate in harsh environments without existing communication infrastructure, requiring the formation of ad-hoc networks to exchange information. Many algorithms for control of multi-robot teams operate under the assumption that low-latency, global state information necessary to coordinate agent actions can readily be disseminated among the team. Our approach leverages GNNs to control the connectivity within the ad-hoc network and to provide the data distribution infrastructure necessary for countless multi-robot algorithms.

Finally, this thesis develops a framework for distributed learning to be used when centralized information is unavailable during training. Our approach allows robots to train controllers independently and then share their experiences by composing multiple models represented in a Reproducing Kernel Hilbert Space.
