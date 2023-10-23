# Wdbc dataset - classification

Data source: https://datahub.io/machine-learning/wdbc

The analyzed data were related to patients with brest cancer. The target variable was "Diagnosis" meaning the type of cance - malignant (M) or benigin (B). A preliminary exploratory analysis was performed - data were read and outliers were removed using n-Sigma method. The data were split into train and test data and Machine Learning models were created. The first one was Logistic Regression (LR), the second one was Naive Bayes Classifier (NBS) and the last one was XGBoost Classifier (XGBC). Various metrics were calculated to evaluate the quality of the classifiers. It was accuracy, precision, recall and f1-score. Additionally - results were presented in the form of Confusion Matrix and ROC curve was shown for each classifier. Despite the fact that the data (target variable) after removing outliers was unbalanced, very good results were obtained. The best results were reached by XGBC classifier. The accuracy and precision was 0.99 and recall value was 0.98. The area under the ROC curve (AUC) was very large for each classifier. In summary - the data analysis and calssification was successful. Each classifier obtained really good results.
