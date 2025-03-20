# EEG Feature Selection for Seizure Detection
This repository summarizes the Python codes for EEG feature selection 

This work was supported in part by the ECE Dept. of UT Dallas under Pathways to Research Scholarship.

**A two-step feature selection approach is presented to enhance EEG seizure detection, where:**

**1. Step 1: Linear discriminant analysis (LDA) for channel ranking;**
**2. Step 2: Feature subset selection using least absolute shrinkage and selection operation (LASSO).**

**The selection procedure is recursively performed, validated on SVM to obtain the optimal results.**

We tested our works on [CHB-MIT Scalp EEG Database (version 1.0.0)](https://doi.org/10.13026/C2K01R), a well-known public EEG dataset for many seizure detection tasks. We achieved F-1 score of 88%, and we are continuing to improve!

Three child branches are introduced as next. Details can be referred in each individual branch:
1. [DTF Calculation](https://github.com/penggenchang/DTF-and-Seizure-Network/tree/DTF-Calculation): This branch implements the Python code for directed transfer function (DTF), a widely-applied directed connectivity metric in EEG data analysis.
2. [Graph Visualization](https://github.com/penggenchang/DTF-and-Seizure-Network/tree/Graph-Visualization): This branch includes different functions to visualize the DTF-based seizure network during analysis.
3. [Related Works](https://github.com/penggenchang/DTF-and-Seizure-Network/tree/Related-Works): This branch lists the other related references that we compare with.

Preliminary work of this research has been reported in the following paper that the readers are suggested to cite:
- G. Peng, M. Nourani, J. Harvey and H. Dave, "Personalized EEG feature selection for low-complexity seizure monitoring," International Journal of Neural Systems, 2021. https://doi.org/10.1142/S0129065721500180
- G. Peng, M. Nourani, J. Harvey and H. Dave, "Personalized feature selection for wearable EEG monitoring platform," 2024 IEEE-EMBS International Conference on Biomedical and Health Informatics (BHI), 2024. https://doi.org/10.1109/BIBE50027.2020.00069
- G. Peng, M. Nourani, J. Harvey and H. Dave, "Feature selection using F-statistic values for EEG signal analysis", 42nd Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC), July 2020. https://doi.org/10.1109/EMBC44109.2020.9176434
