---
layout: page
title: Location based social networks
description: Efficient embedding for hypergraphs
img:
importance: 1
category: 
redirect: false
url: true
---

My work was centered around the application of hypergraphs to location-based social
networks (LBSNs). Under the guidance of [Prof. Srijith P K](https://sites.google.com/site/pksrijith/home) and [Manisha Dubey](https://sites.google.com/view/brainiith/people?authuser=0), I started with implementing the LBSN2Vec algorithm in Python. For LBSN, the network can be modeled into a k-uniform hypergraph, so I compared the results of location prediction using a perceptron based architecture, DHNE and a random walk based architecture, LBSN2Vec. The LBSN2Vec algorithm uses the social network as an additional information as compared to the DHNE algorithm. In order to remove that, I modified the former to not use the friendship graph. Instead, to achieve the random walk with stay procedure, I operated the random walk on a shuffled sequence of locations ids and for each node on that walk, sampled nodes from the other 3 domains. 
