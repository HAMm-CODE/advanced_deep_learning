# Graph Convolutional Networks (GCN) on OGBN-Arxiv

## Overview
This project implements a Graph Convolutional Network (GCN) with PyTorch Geometric and evaluates node classification performance on the OGBN-Arxiv dataset from the Open Graph Benchmark (OGB).

## Highlights
- Built a multi-layer GCN with batch normalization, ReLU, dropout, and log-softmax output.
- Trained and evaluated the model using OGB-provided train/valid/test splits and evaluator.
- Worked with large-scale citation graph data and sparse adjacency representations.

## Tech Stack
- Python, PyTorch, PyTorch Geometric (PyG)
- OGB (Open Graph Benchmark)
- NumPy

## Files
- Exercise4_solution.ipynb: Full implementation, training loop, and evaluation.

## How to Run
1. Open Exercise4_solution.ipynb.
2. Install dependencies:
   - torch_geometric
   - ogb
3. Run the notebook cells in order (GPU recommended).

## Notes
- Dataset: ogbn-arxiv (node classification on a citation graph).
- The notebook includes all model, training, and evaluation code.
