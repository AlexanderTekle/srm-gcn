Graph Convolutional Networks for SRM
======================================
* This repository contains code using Pytorch Geometric to build a Graph Convolutional Network binary classifier on a dataset of 1000 randomly created graphs with a labeled encoding score.
* adjs.npy contain the adjacency matrix for 1000 randomly created graphs. Encodings.csv contain the encoding score for the sparse and dense graph, and encodings(catx-orix)2.csv represent the score improvement for each sparse graph.
* srm-gcn.ipynb is a python notebook to preprocess our dataset and setup the GCN model. 

Useful resources:
======================================
* https://github.com/rusty1s/pytorch_geometric/blob/master/examples/gcn.py
* https://tkipf.github.io/graph-convolutional-networks/
* https://arxiv.org/abs/1609.02907
