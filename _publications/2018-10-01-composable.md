---
title: "Composable Learning with Sparse Kernel Representations"
collection: publications
permalink: /publication/2018-10-01-composable
excerpt: '<a href="https://arxiv.org/pdf/2103.14474.pdf"> [Paper] </a> <a href="https://youtu.be/kWIigy5MWdU"> [Video] </a> <a href="http://katetolstaya.github.io/files/Composable_Learning_Poster.pdf"> [Poster] </a> <a href="http://katetolstaya.github.io/files/Composable_Learning_slides.pdf"> [Slides] </a> <a href="https://github.com/katetolstaya/kernelrl"> [Code] </a> '
date: 2018-10-1
venue: 'International Conference on Intelligent Robots and Systems'
---

<a href="https://arxiv.org/pdf/2103.14474.pdf"> [Paper] </a> <a href="https://youtu.be/kWIigy5MWdU"> [Video] </a> <a href="http://katetolstaya.github.io/files/Composable_Learning_Poster.pdf"> [Poster] </a> <a href="http://katetolstaya.github.io/files/Composable_Learning_slides.pdf"> [Slides] </a> <a href="https://github.com/katetolstaya/kernelrl"> [Code] </a>

We present a reinforcement learning algorithm for learning sparse non-parametric controllers in a Reproducing Kernel Hilbert Space.  
We improve the sample complexity of this approach by imposing a structure of the state-action function through a normalized advantage function (NAF). This representation of the policy enables efficiently composing multiple learned models without additional training samples or interaction with the environment.
We demonstrate the performance of this algorithm on learning obstacle-avoidance policies in multiple simulations of a robot equipped with a laser scanner while navigating in a 2D environment. We apply the composition operation to various policy combinations and test them to show that the composed policies retain the performance of their components. We also transfer the composed policy directly to a physical platform operating in an arena with obstacles in order to demonstrate a degree of generalization.
