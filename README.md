论文：Can Cheng， Bing Li*， Zengyang Li， Peng Liang， Xu Yang. An in-depth study of the effects of methods on the dataset selection of public development projects. IET Software. 2021，1-21. 

# GitHub_study
We provide these files as the Supplementary material of our study.
(1) Experiment 1. This folder contains our dataset for experiment 1. The dataset contains id, the basic features (e.g., star number), PDP label, and DPDP label.
(2) Experiment 2. This folder contains six datasets for experiment 2. Each CSV file contains different feature sets and label results. For example, dpdp_level_basic contains all features in Level basic (details can be find in our study) and DPDP labels.
(3) Labels. This folder contains dataset of our labels. The dataset contains project id, ten sub-labels (e.g., Wiki), and corresponding project links. The inconsistencies between two researchers are labeled with * mark in the provided dataset.
(4) Dataset for additional experiment in Table 7 and Table 8. This folder contains the trainned model in the study and the corresponding samples selected by specific strategies. For example, we can load J48+Level_readme+DPDP.model in the weka software and predict c_dpdp.csv. Then, we can get the results of the combination of the J48 method (with the configuration of level_README) and the selecting projects with C programming language method.

我们提供这些文件作为我们研究的补充材料。
(1) Experiment 1。此文件夹包含我们实验1的数据集。数据集包含id、基本特征（如星标数量）、PDP标签和DPDP标签。
(2) Experiment 2。此文件夹包含实验2的六个数据集。每个CSV文件包含不同的特征集和标签结果。例如，dpdp_level_basic包含Level basic中的所有特征（详情可在我们的研究中找到）以及DPDP标签。
(3) Labels。此文件夹包含我们标签的数据集。数据集包含项目id、十个子标签（如Wiki）以及相应的项目链接。两位研究人员之间的不一致项在提供的数据集中用*标记。
(4) Dataset for additional experiment in Table 7 and Table 8。此文件夹包含研究中训练的模型和通过特定策略选择的相应样本。例如，我们可以在weka软件中加载J48+Level_readme+DPDP.model并预测c_dpdp.csv。然后，我们可以获得J48方法（使用level_README配置）与选择C编程语言项目方法组合的结果。
