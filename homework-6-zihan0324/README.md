# Homework 6
## APS Failure Data
1. Data Preparation:
	a. Deal with missing value
	b. Pick $\lfloor 170 \rfloor$ features with highest CV, and make scatter plots and box plots for them
2. Train a random forest to classify the data set. Do NOT compensate for class imbalance in the data set
3. Compensate for class imbalance in your random forest and repeat training process
4. Use XGBoost to fit the model tree for the APS data set without compensation for class imbalance.
5. Use SMOTE (Synthetic Minority Over-sampling Technique) to pre-process your data to compensate for class imbalance. Train XGBosst with L1-penalized logistic regression at each node using the pre-processed data and repeat previous step.
