## Challenges

- **Data leakage risk**  
  Standard node classification splits are not suitable for link prediction. Edge-level splitting was required to ensure no leakage between train and test sets.

- **Negative sampling design**  
  Choosing an appropriate ratio of positive to negative edges was important, as imbalance affected model performance and stability.

- **Model comparison fairness**  
  Ensuring all models were evaluated under the same pipeline was necessary to isolate architectural differences.

- **Sparse vs dense graph behavior**  
  Models behaved differently depending on graph structure, making it challenging to generalize findings across datasets.

- **Scalability and robustness**  
  Handling large graphs (PubMed) and designing meaningful corruption experiments required careful implementation.
