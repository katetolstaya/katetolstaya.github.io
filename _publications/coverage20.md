---
title: "Multi-Robot Coverage and Exploration using Spatial Graph Neural Networks"
collection: publications
permalink: /publication/2020-coverage
excerpt: '<a href="https://arxiv.org/pdf/2011.01119.pdf"> [Paper] </a> <a href="https://youtu.be/MiYSeENTyoA"> [Demo Video] </a>   <a href="https://github.com/katetolstaya/graph_rl"> [Code] </a> '
date: 2020-11-2
venue: 'ArXiv'
---

<a href="https://arxiv.org/pdf/2011.01119.pdf"> [Paper] </a> <a href="https://youtu.be/MiYSeENTyoA"> [Demo Video] </a>   <a href="https://github.com/katetolstaya/graph_rl"> [Code] </a> 

 <img src='/images/coverage_fig.png'>

The multi-robot coverage problem is an essential building block for systems that perform tasks like inspection, exploration, or search and rescue. We discretize the coverage problem to induce a spatial graph of locations and represent robots as nodes in the graph. Then, we train a Graph Neural Network controller that leverages the spatial equivariance of the task to imitate an expert open-loop routing solution.  This approach generalizes well to much larger maps and larger teams that are intractable for the expert. In particular, the model generalizes effectively to a simulation of ten quadrotors and dozens of buildings in an urban setting. We also demonstrate the GNN controller can surpass planning-based approaches in an exploration task. 
