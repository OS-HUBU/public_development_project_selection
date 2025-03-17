# GitHub_study
We provide these files as the Supplementary material of our study.
(1) Experiment 1. This folder contains our dataset for experiment 1. The dataset contains id, the basic features (e.g., star number), PDP label, and DPDP label.
(2) Experiment 2. This folder contains six datasets for experiment 2. Each CSV file contains different feature sets and label results. For example, dpdp_level_basic contains all features in Level basic (details can be find in our study) and DPDP labels.
(3) Labels. This folder contains dataset of our labels. The dataset contains project id, ten sub-labels (e.g., Wiki), and corresponding project links. The inconsistencies between two researchers are labeled with * mark in the provided dataset.
(4) Dataset for additional experiment in Table 7 and Table 8. This folder contains the trainned model in the study and the corresponding samples selected by specific strategies. For example, we can load J48+Level_readme+DPDP.model in the weka software and predict c_dpdp.csv. Then, we can get the results of the combination of the J48 method (with the configuration of level_README) and the selecting projects with C programming language method.
