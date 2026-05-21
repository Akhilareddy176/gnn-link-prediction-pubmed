## Experimental Stages

The project is organized into three main stages:

- **Core Evaluation**  
  Baseline performance of all models (GCN, GraphSAGE, GAT, VGAE) is evaluated under a shared pipeline.

- **Grid Search**  
  Hyperparameters such as learning rate, dropout, and weight decay are tuned based on validation performance.

- **Robustness Analysis**  
  The best-performing models are evaluated under feature masking and edge removal to assess stability under graph corruption.
