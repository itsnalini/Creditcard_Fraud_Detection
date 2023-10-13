# Creditcard Fraud Detection using Scikit-Learn

# Objectives:
- Perform basic data preprocessing in Python
- Model a classification task using the Scikit-Learn
- Train Support Vector Machine and Decision Tree using Scikit-Learn
- Run inference and access the quality of the trained models

# Methodology:
- Dataset Analysis
- Data Preprocessing
- Dataset Train/ Test Split
- Build a Decision Tree Classifier model
- Evaluate the Decision Tree Classifier model
- Build a Support Vector Machine model
- Evaluate the Support Vector Machine model

# Findings:
- There are 284807 observations with 31 variables in the dataset
- The dataset is highly unbalanced which 99.827% of the transaction is legitimate and 0.173% of the transactions is fraudulent. Therefore, this case would require special attention when training or when evaluating the quality of a model.
- The Tree Classifier models has the ROC-AUC score of 0.966 and the Support Vector Machine models has the ROC-AUC score of 0.984. Both model perform well in predicting the feature (Fradulent transaction).
