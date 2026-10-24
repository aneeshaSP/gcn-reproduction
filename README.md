# gcn-reproduction
## Goal
Reproduce a basic Graph Convolutional Network (GCN) for semi-supervised node classification on the Cora citation network, following the paper:

*Kipf and Welling, Semi-Supervised Classification with Graph Convolutional Networks (2017).*

## Objectives
- Understand the architecture and graph convolution operation.
- Implement a two-layer GCN.
- Train and evaluate the model on the Cora dataset.
- Compare the results with the paper's reported performance.
- Document the experimental setup, results, and reproduction challenges.

## Dataset
**Cora** — a citation network in which papers are represented as nodes, citations as edges, and paper topics as class labels.

## Planned Tech Stack
- Python
- PyTorch
- PyTorch Geometric
- Cora citation dataset

## Reproduction Scope
This project initially focuses on reproducing the basic two-layer GCN for node classification. Extensions and experiments will be added after establishing a working baseline.

## Status
- [ ] Set up the environment
- [ ] Load and inspect the Cora dataset
- [ ] Implement the GCN model
- [ ] Train and evaluate the model
- [ ] Record results and compare against the reference paper

## Reference
Kipf, T. N., & Welling, M. (2017). *Semi-Supervised Classification with Graph Convolutional Networks.*
Paper: https://arxiv.org/abs/1609.02907
