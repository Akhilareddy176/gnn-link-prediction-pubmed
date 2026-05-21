## Implementation

The pipeline is implemented using PyTorch and PyTorch Geometric.

- Citation datasets are loaded using built-in Planetoid loaders  
- Edge splits are created using RandomLinkSplit for link prediction  
- GNN encoders (GCN, GraphSAGE, GAT, VGAE) are implemented as two-layer models  
- A dot-product decoder is used for edge scoring  
- Training is performed using the Adam optimizer  
- Evaluation metrics (ROC-AUC, AP) are computed using predicted edge scores  

A modular structure is followed with separate components for data processing, models, training, evaluation, and robustness experiments.
