## Models Used

Four Graph Neural Network architectures are evaluated:

- **GCN (Graph Convolutional Network):** Neighbor information is aggregated using normalized averaging; effective for homophilous graphs  
- **GraphSAGE:** Neighbor features are sampled and aggregated; provides flexibility with increased complexity  
- **GAT (Graph Attention Network):** Attention weights are assigned to neighbors to learn their importance  
- **VGAE (Variational Graph Autoencoder):** Probabilistic node embeddings are learned and links are reconstructed  

These models represent different approaches to learning from graph structure and node features.
