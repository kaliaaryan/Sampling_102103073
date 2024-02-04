### CREDIT CARD PROBLEM USING SAMPLING

1. Converted imbalanced dataset to balanced dataset using overfitting sampling technique using SMOTE. <br>
2. Used four different sampling techniques such as: <br>
   a) Simple Random Sampling (S1)
   b) Stratified Sampling (S2)
   c) Cluster Sampling (S3)
   d) Systematic Sampling (S4)

3. Applied five different models on each sample, such as: <br>
   a) Logistic Regression (LR)
   b) Naive Bayes Classifier (NB)
   c) Random Forest Classifier (RF)
   d) Decision Tree Classifier (DT)
   e) K-Nearest Neighbours (KNN)

The Accuracy Results are summarized in the table below:


|   Sampling   |   LR    |   NB    |   RF   |   DT    |   KNN    |
|--------------|---------|---------|--------|---------|----------|
|   S1         |  0.8839 | 0.7806  | 0.9742 | 0.9290  |  0.8645  |
|   S2         |  0.8645 | 0.7355  | 0.8710 | 0.7355  |  0.7548  | 
|   S3         |  0.8516 | 0.7935  | 0.9742 | 0.8516  |  0.7226  |
|   S4         |  0.8516 | 0.4839  | 0.9742 | 0.9548  |  0.8322  |

The best highest accuracy acore is given by Random Forest for Simple Random, Cluster and Systematic Sampling i.e., 0.9742 respectively.
