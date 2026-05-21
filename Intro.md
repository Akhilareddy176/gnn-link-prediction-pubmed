## Problem: Link Prediction

Link prediction aims to determine whether an edge should exist between two nodes in a graph.

In this project, the graph is a citation network:
- G = (V, E)  
- V (nodes) = papers  
- E (edges) = citations  

Goal: predict missing edges.
---
## Graph Neural Networks (GNNs)

GNNs learn from graph-structured data by aggregating information from neighboring nodes to create meaningful representations.

By using both graph structure and node features, they can predict links between nodes.

---

## Applications

- Citation networks: paper recommendation, missing citation discovery  
- Social networks: friend recommendation  
- E-commerce: product recommendation  
- Fraud detection: suspicious activity  
- Biology: protein interactions  
- Knowledge graphs: relation prediction
  
## Limitations of Traditional Methods

Traditional link prediction methods use graph heuristics like common neighbors or Jaccard similarity.

However:
- They use only graph structure and ignore node features  
- They rely on fixed rules instead of learning patterns  
- They do not generalize well  

---

## Approach

 Graph Neural Networks (GNNs) are used to overcome these limitations.

GNNs learn node embeddings by combining information from neighbors and node features, capturing both structure and similarity.This allows the model to capture both structural patterns and feature similarity.

For link prediction:
- Nodes are encoded into embeddings  
- A scoring function (e.g., dot product) predicts whether an edge exists between node pairs  

This enables the model to learn complex relationships beyond simple graph heuristics.
Graph structure
Node features
