---
layout: post
title: Winter Is Coming
---

CodeKernel: A Graph Kernel based Approach to the Selection of API Usage Examples

API usage examples, cluster and summarize, method invocation sequences, feature vector.
CodeKernel, graph kernel, object usage graph, cluster graph by graph kernel embedding, select representative graph.

State-of-the-art approaches: 
Call sequence without structural information; 
Feature vector is insufficient to capture structural information;
Code clone detection could produce redundant examples; 
Graph based frequent pattern mining.

Graph Kernel: graphs -> pair-wise inner products similarity matrix.

1. Graph representation: GrouMiner at function level, 
2. Graph Kernel -> positive definite kernel matrix (pair-wise similarity),
3. Spectral cluster,
4. Representative selection, centrality, specificity, 
![alt text]({{ site.baseurl }}/images/2019/11/centrality.png "image alt"){: .center-image }
![alt text]({{ site.baseurl }}/images/2019/11/specificity.png "image alt"){: .center-image }
![alt text]({{ site.baseurl }}/images/2019/11/representative-score.png "image alt"){: .center-image }
Representative score: 

\\
\\
TBD: [Frequent pattern mining](https://www.jianshu.com/p/06c085e6a1a7),  [Spectral cluster](https://blog.csdn.net/qq_24519677/article/details/82291867)
