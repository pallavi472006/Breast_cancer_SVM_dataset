# Breast_cancer_SVM_dataset
This project demonstrates the application of Support Vector Machines (SVM) for binary classification tasks, specifically distinguishing between malignant and benign breast cancer tumors. Utilizing the Breast Cancer Wisconsin (Diagnostic) dataset from scikit-learn, the project aims to develop a machine learning model capable of accurately classifying tumor samples based on various features.
1.	Data Preprocessing: Loaded the dataset and separated features (X) from the target labels (y). Split the data into training (80%) and testing (20%) sets. Standardized the features using StandardScaler to ensure all features contribute equally to the model's performance.
2.	Model Development: Implemented SVM classifiers with both linear and Radial Basis Function (RBF) kernels. Trained the models on the training set and evaluated their performance on the test set.
3.	Model Evaluation: Assessed model performance using metrics such as accuracy, precision, recall, and F1-score. Visualized decision boundaries for the linear kernel to understand model behavior.
4.	Hyperparameter Tuning: Applied GridSearchCV to optimize hyperparameters like C and gamma for the RBF kernel. Evaluated the best model using cross-validation to ensure robustness.
•	Linear Kernel SVM: Achieved an accuracy of approximately 96% on the test set.
•	RBF Kernel SVM: Achieved an accuracy of approximately 97% on the test set after hyperparameter tuning.
•	SVMs are effective for binary classification tasks, especially with clear margins of separation.
•	The choice of kernel significantly impacts model performance; the RBF kernel is more flexible in capturing complex patterns.
•	Standardization of features is crucial for SVM performance, as it ensures all features are on a similar scale.

