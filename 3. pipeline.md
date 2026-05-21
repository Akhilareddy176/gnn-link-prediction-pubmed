## Pipeline

The link prediction task is formulated as a binary classification problem on node pairs.

1. **Data Preparation**  
   The citation graph is loaded and node features are normalized.

2. **Edge Splitting**  
   Edges are split into train, validation, and test sets.  
   Validation and test edges are removed from the training graph to prevent data leakage.

3. **Negative Sampling**  
   For each positive edge, a negative (non-existing) edge is sampled to create a balanced dataset.

4. **Encoding**  
   Node features and graph structure are passed through a GNN encoder to generate node embeddings.

5. **Decoding**  
   A scoring function (dot product) is used on node embeddings to predict the likelihood of an edge.

6. **Training**  
   The model is trained using binary cross-entropy loss on positive and negative edges.

7. **Evaluation**  
   Performance is measured using ROC-AUC and Average Precision (AP).
