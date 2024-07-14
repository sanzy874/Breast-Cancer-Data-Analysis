# Breast-Cancer-Data-Analysis
Data was analysed, predicted and validated

Question/Problem statement: Use Bayesian Classifier to classify Breast Cancer 
Data. Determine the accuracy of the Classifier. Write the outcome. 

Title: Predicting Breast Cancer Diagnosis using Machine Learning. 

Methodology used:  
• Data Preprocessing: Removed trivial columns, handled missing values by filling them with 
class-specific means, and split the data into training and testing sets using stratified 
sampling. 
• Model Training: Employed the Gaussian Naive Bayes classifier to train the model on the 
training set. 
• Model Evaluation: Calculated the accuracy of the classifier on the testing set to assess its 
performance. 
Results Obtained: 
• Achieved an accuracy of 95.71% with the Bayesian classifier on the testing set. 
• Class-specific means of the "Bare.nuclei" feature revealed significant differences between 
benign and malignant tumors, indicating its importance in distinguishing between the two 
classes. 

Learning and Highlights Revealed: 
• Class-specific means provided insights into the distribution of the "Bare.nuclei" feature, 
highlighting its role in distinguishing between benign and malignant tumors. 
• By preserving the class distribution in both the training and testing sets, stratified sampling 
improved the validity of the model evaluation procedure. 
• Stratified sampling- A method of sampling that involves the division of population into 
smaller subgroups known as strata. 
• Gaussian Naive Bayes is a classification technique used in machine learning based on a 
probabilistic approach and Gaussian distribution. Gaussian Naive Bayes assumes that each 
parameter, also called features or predictors, has an independent capacity of predicting the 
output variable.
