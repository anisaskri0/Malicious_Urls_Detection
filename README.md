In this project, 
we compared two machine learning models for phishing URL detection: Logistic Regression and Multinomial Naive Bayes (MNB). After evaluating their performance,
we found that Logistic Regression outperforms MNB in terms of accuracy and classification metrics. To streamline our workflow, we utilized scikit-learn's pipeline functionality, 
which allows for efficient integration of data preprocessing and model training steps. The pipeline incorporates CountVectorizer to transform URL text into feature vectors and 
then applies Logistic Regression for classification. This modular approach not only simplifies the code but also enhances the model's adaptability for future improvements and hyperparameter tuning.
