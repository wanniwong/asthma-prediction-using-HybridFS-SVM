# Prediction of Asthma from Single Nucleotide Polymorphism using Support Vector Machine with Feature Selection

As the most common genetic variation responsible for trait and disease, single nucleotide polymorphism (SNP) has been studied extensively in disease research. Nevertheless, the high dimensional SNP tends to cause overfitting and thereby lower prediction performance. This research is aimed to propose a hybrid feature selection to identify significant SNPs, followed by SVM model to predict asthma. Results show that the proposed model is outperformed the existing model with an average accuracy, precision, recall, and AUC of 98.91%, 98.36%, 99.72% and 0.99 when considering 350 SNPs. The top five selected SNPs has been reviewed through biological context and some genes of the SNPs such as RNF217 and AKAP6 are found correlated with respiratory diseases.

* The dataset is collected from Gaudillo et al. (2019) at https://github.com/jdgaudillo/SNP-ML.
* [**data_encoding.ipynb**](data_encoding.ipynb) is to transform SNP data from character to numeric.
* [**hybridFS-SVM.ipynb**](hybridFS-SVM.ipynb) is to predict asthma from SNP using the proposed model HybridFS-SVM.
