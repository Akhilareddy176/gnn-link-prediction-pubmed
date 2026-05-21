## Problem: Link Prediction

Link prediction aims to determine whether an edge should exist between two nodes in a graph.

In this project, the graph is a citation network:
- Nodes = papers  
- Edges = citations  

Formally: G = (V, E), where V = papers and E = citations.  
Goal: predict missing edges.

The model uses graph structure and node features to identify potential links, enabling tasks like recommending relevant papers or discovering related research.

---

## Graph Neural Networks (GNNs)

GNNs learn from graph-structured data by aggregating information from neighboring nodes to generate meaningful representations.

---

## Applications (beyond citation networks)

- Social networks: friend recommendation  
- E-commerce: product recommendation  
- Fraud detection: suspicious activity  
- Biology: protein interactions, drug discovery  
- Knowledge graphs: relation prediction

## Limitations of Traditional Methods

Traditional link prediction methods rely on graph heuristics such as common neighbors, Jaccard similarity, or preferential attachment.

These approaches fail because:
- They use only graph structure and ignore node features  
- They rely on hand-crafted rules instead of learning patterns  
- They do not generalize well across different graphs  

As a result, they cannot capture complex relationships that GNNs can learn from both structure and features.


Graph structure
Node features
