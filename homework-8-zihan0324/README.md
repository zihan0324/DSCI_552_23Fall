# Homework 8
## Breast Cancer Wisconsin (Diagnostic) Data Set
**Monte-Carlo Simulation**:
Repeat the following procedures for supervised, un- supervised, and semi-supervised learning M = 30 times, and use randomly se- lected train and test data (make sure you use 20% of both the positve and nega- tive classes as the test set). Then compare the average scores (accuracy, precision, recall, F1-score, and AUC) that you obtain from each algorithm.
1. Supervised Learning
2. Semi-Supervised Learning/ Self-training
3. Unsupervised Learning
4. Spectral Clustering


## Banknote Authentication Data Set
**Monte-Carlo Simulation**:
Repeat each of the following two procedures 50 times. You will have 50 errors for 90 SVMs per each procedure.
1. **Passive Learning**: Train a SVM with a pool of 10 randomly selected data points from the training set using linear kernel and L1 penalty. Select the penalty parameter using 5-fold cross validation. Repeat this process by adding 10 other randomly selected data points to the pool, until you use all the 900 points. Do NOT replace the samples back into the training set at each step. Calculate the test error for each SVM. You will have 90 SVMs that were trained using 10, 20, 30, ... , 900 data points and their 90 test errors.
2. **Active Learning**: Traina SVM with a pool of 10 randomly selected data points from the training set using linear kernel and L1 penalty. Select the parameters of the SVM with 5-fold cross validation. Choose the 10 closest data points in the training set to the hyperplane of the SVM and add them to the pool. Do not replace the samples back into the training set. Train a new SVM using the pool. Repeat this process until all training data is used. You will have 90 SVMs that were trained using 10, 20, 30,..., 900 data points and their 90 test errors.
