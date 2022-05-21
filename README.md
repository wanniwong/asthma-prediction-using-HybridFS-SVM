# Prediction of Asthma from Single Nucleotide Polymorphism using Support Vector Machine with Feature Selection

As the most common genetic variation responsible for trait and disease, single nucleotide polymorphism (SNP) has been studied extensively in disease research. Nevertheless, the high dimensional SNP tends to cause overfitting and thereby lower prediction performance. This research is aimed to propose a hybrid feature selection to identify significant SNPs, followed by a SVM model to predict asthma. Results show that the proposed model is outperformed the existing model with an average accuracy, precision, recall, and AUC of 98.91%, 98.36%, 99.72% and 0.99 when considering 350 SNPs. The top five selected SNPs has been reviewed through biological context and some genes of the SNPs such as RNF217 and AKAP6 are found correlated with respiratory diseases.

(1) Data collection - SNP dataset is collected from Gaudillo et al. (2019) at https://github.com/jdgaudillo/SNP-ML

(2) Data transformation - Transform SNP data from character to numeric (Please refer [**data_transformation.ipynb**](data_transformation.ipynb))

(3) Feature selection and Classification - Predict asthma from SNP (Please refer [**hybridFS-SVM.ipynb**](hybridFS-SVM.ipynb))
