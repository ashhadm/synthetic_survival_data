# Generating Accurate Synthetic Survival Data by Conditioning on Outcomes

Abstract: Synthetically generated data can improve privacy, fairness, and data accessibility; however, it can be challenging in specialized scenarios such as survival analysis. One key challenge in this setting is censoring, i.e., the timing of an event is unknown in some cases. Existing methods struggle to accurately reproduce the distributions of both observed and censored event times when generating synthetic data. We propose a conceptually simple approach that generates covariates conditioned on event times and censoring indicators by leveraging existing tabular data generation models without making assumptions about the mechanism underlying censoring. Experiments on real-world datasets demonstrate that our method consistently outperforms baselines and improves downstream survival model performance

To run the experiments in the paper, simply use the Jupyter notebooks for the respective experiments and add the path to the datasets (only for AIDS and FLCHAIN, other datasets will be imported automatically).

To adapt existing tabular models for survival data generation using the proposed methodology in our paper, changes were made to the Synthcity Library [1]. These changes can be found at : https://github.com/anonymous-785/synthcity . All rights to the Synthcity library are reserved by the original authors.

[1] Qian, Zhaozhi, Rob Davis, and Mihaela van der Schaar. "Synthcity: a benchmark framework for diverse use cases of tabular synthetic data." Advances in Neural Information Processing Systems 36 (2024).
