---
layout: project
type: project
image: img/sea-network/island.png
title: "Network of Routes: Sea of Islands"
date: 2023
published: true
labels: 
  - Algorithms
  - Weighted Graphs
  - Fruchterman-Reingold
summary: "I was part of a team that used algorithms to plan a network of routes that efficiently distributed goods and facilitated travel among the islands in the Polynesian Triangle in ICS 311."
---
<img width="175px" class="rounded float-start pe-4" src="https://www.boost.org/doc/libs/1_53_0/libs/graph/doc/figs/embedding_illustration.png"> 

## Planarity with Sea of Islands
The initial problem space tasked our group with creating a system of travel paths to various islands within the Polynesian Triangle. For this, we represented the Sea of Islands with a directed, weighted graph. Here, each island is a node, and the routes that corresponded to different travel times were the edges. Since each island has unique traits such as population resources, educational material, distinct travel experiences, and native items, our group's primary concern was to find ways in which to circulate these types of needs as well as the fluid movement of people among the Sea of Islands. 

In an expansion project, each team member was responsible for describing an algorithm that amplified the original submission to further improve the quality of life and shared resources within the Sea of Islands. My section discussed the issue of looking at the planarity of the Sea of Islands as a graph, with the main concern being the optimization of routes so that the edges connecting the nodes o not overlap as much as possible. Doing this allows the representation of the islands to look visually more appealing and simpler to understand. Even with a wide range of connections, the graph would be more user-friendly and easier to interpret, especially with the supplying process. 

<img width="175px" class="rounded float-start pe-4" src="https://www.researchgate.net/publication/301217160/figure/fig9/AS:359956277678080@1462831674860/Force-directed-layout-Fruchterman-Reingold-algorithm-of-an-example-ground-truth-network.png"> 

## Choice of Algorithm
I chose to use a modified version of a Fruchterman-Reingold algorithm as a way of minimizing the number of edge crossings within the graph. With this, it will iteratively look to adjust the node and edge positions to create a less-jumbled mess of a layout. Here, the travel times are the edge weights and considers directional forces in order to better represent the distribution of both resources and people. The algorithm stops when the changes in reducing the amount of overlaps become slower, and iteratively adjusts the positions of the islands depending on the nature of forces between the islands. Ulimately, I decided on using F-R over Kamada-Kawai since the latter is more effcient with large datasets, is faster, and easier to implement given the problem space over K-K. 

Here is a [link](https://github.com/k-deguz/k-deguz.github.io/blob/main/img/sea-network/Final%20Write%20Up%20ICS%20311%20(1).pdf) to the essay.
 

