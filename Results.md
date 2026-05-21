## Results & Key Findings

- **GCN** achieves the strongest overall performance on the PubMed dataset  
- **VGAE** performs competitively but is slightly lower due to regularization effects  
- **GraphSAGE** and **GAT** underperform compared to GCN  

### Robustness Analysis

- Performance degrades gradually under feature masking and edge removal (up to 30%)  
- High accuracy is retained, indicating robustness to missing data  
- This suggests reliance on distributed structural patterns rather than individual features or edges  

Overall, simple GCN-based aggregation proves to be an effective and reliable approach for link prediction on large citation networks.
