# Homework 7
## Anuran Calls (MFCCs) Data Set
### Multi-class and Multi-Label Classification Using Support Vector Machines
1. Train a SVM for each of the labels (Families, Genus, and Species), using Gaussian kernels and one versus all classifiers
2. Repeat training process with L1-penalized SVMs
3. Repeat training process by using SMOTE or any other method that can remedy class imbalance

### K-Means Clustering on a Multi-Class and Multi-Label Data Set Monte-Carlo Simulation
Perform the following procedures 50 times, and report the average and standard deviation of the 50 Hamming Distances that you calculate.
1. Use k-means clustering on the whole Anuran Calls (MFCCs) Data Set (do not split the data into train and test, as we are not performing supervised learning in this exercise). Choose k ∈ {1, 2, . . . , 50} automatically based on one of the methods (CH or Gap Statistics or scree plots or Silhouettes) or any other method you know
2. In each cluster, determine which family is the majority by reading the true labels. Repeat for genus and species
3. Now for each cluster you have a majority label triplet (family, genus, species). Calculate the average Hamming distance, Hamming score, and Hamming loss between the true labels and the labels assigned by clusters.
