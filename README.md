# NFTDefects

This is the repository of our work on the definition and detection of defects in NFT smart contracts.
Please **enter into** each directory for further information (with a `README` file per directory).

### dataset_for_defining_defects

The dataset that we use to define the 5 defects. The `defect_map.csv` stores the mapping relationship between inputs (i.e., posts and reports) and the 5 defect types.

### experiment

The results of our conducted experiments.

- Comparison with the other 6 tools (with outputs of them)
- Results of large-scale experiment on 16,527 NFT smart contracts.
- Evaluation results of related experiments.
  - labeled results on randomly sampled dataset with a confidence interval of 10 and a confidence level of 95% for **precision** and **false positives** evaluation.
  - analysis of **false negatives** by the same sampling approach on contracts where no defect was reported.
  - effectiveness evaluation of **proposed solutions** for each defect.

### NFTGuard

The source code of our tool with a detailed `README`.
