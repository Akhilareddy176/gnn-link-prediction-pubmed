## Conclusion

GNN-based models effectively learn from both graph structure and node features for link prediction. Among the evaluated models, GCN provides the best overall performance and stability on the PubMed dataset, while VGAE serves as a strong alternative due to its latent representation learning.

Results show that model performance depends on the interaction between architecture and graph structure, with simple aggregation methods often outperforming more complex approaches.

Robustness analysis demonstrates that performance degrades gradually under feature and edge corruption, indicating that predictions rely on distributed structural patterns rather than individual nodes or edges.
