About this project:
In this project, 
we compared two machine learning models for phishing URL detection: Logistic Regression and Multinomial Naive Bayes (MNB). After evaluating their performance,
we found that Logistic Regression outperforms MNB in terms of accuracy and classification metrics. To streamline our workflow, we utilized scikit-learn's pipeline functionality, 
which allows for efficient integration of data preprocessing and model training steps. The pipeline incorporates CountVectorizer to transform URL text into feature vectors and 
then applies Logistic Regression for classification. This modular approach not only simplifies the code but also enhances the model's adaptability for future improvements and hyperparameter tuning.

Dataset Overview :
The dataset used in this project contains 549,346 unique entries with no missing values, providing a robust foundation for our analysis. It consists of two columns: the first is the URL, and the second is the label column, which serves as the prediction target. The label column contains two categories: Good (indicating that the URL does not contain malicious content and is not a phishing site) and Bad (indicating that the URL contains malicious content and is classified as a phishing site). This well-defined dataset allows for effective training and evaluation of our machine learning models in detecting phishing URLs.

