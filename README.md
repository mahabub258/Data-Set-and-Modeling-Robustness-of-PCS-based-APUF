# Data Set of PCS based APUF
PCS based APUF has been implemented on both Spartan-3E and Artix-7 FPGA. Necessary, comments are attached with the file.
# Modeling-Robustness-of-PCS-based-APUF-using-SVM
Modeling attack on PCS based APUF using SVM.
SVM has been implemented using sklearn library Python. The dataset contains 100000 random CRPs. We have run the SVM from 10000 to 100000 CRPs with different number of CRPs. SVM has been run with 'poly', 'rbf' and 'sigmoid' kernel to find the best parameters and modeling accuracy. The best parameters, accuracy and the minimal number of CRPs (to achieve that accuracy) is reported in the file SVM_ATTACK_RESULTS.xlsx.

