# ML-Projects

In this repository, different machine-learning projects are uploaded. All projects are for practice purposes. 

>Iris: In this file, the iris dataset is used from sklearn. This dataset has 150 observations, 4 features (sepal length, sepal width, petal length, petal width) and a target column which tell us the flower specie (setosa, versicolor, virginica).  Data is already cleaned so EDA was not required. The logistic Regression model is used with an SGA solver. Cross-validation is also used to train and test the model on whole data. Accuracy is used as an evaluation metric for this model.

>Digits: This file used the mnist dataset. Logistic regression is used for classification.


>Brest_cancerlr: This file uses The breast cancer dataset from the sklearn library. It has two output labels, 0 for malignant and 1 for benign. Gaussian Naive Bayes is used for this data. Accuracy, recall, precision, and f1_score are used as evaluation metrics.


>Text_data: In this file, the sample text data file has 2 columns, document and label. and have two labels, positive and negative. Firstly Naive Bayes is applied using BOW and evaluation and prediction are performed. Then Naive Bayes is applied using TFIDF and model evaluation and prediction is performed.


>Cancer: In this file, sample data has two columns, gene1, gene2 and a target column having 0 and 1, whether a person has cancer or not. We use KNN for this problem. Data is perfectly balanced, we use GridSearchCV to find the best parameter. At last, the model is deployed using Streamlit.


>breast_cancer: This file uses The breast cancer dataset from the sklearn library. It has two output labels, 0 for malignant and 1 for benign. KNN is used for this data. GridSearchCV is used to find the best parameter. Accuracy, recall, precision, and f1_score are used as evaluation metrics.

>Titanic: In this file titanic dataset is used. It is an end-to-end project. Firstly, EDA is performed which includes missing value imputation, feature engineering, and encoding. Then cross-validation is used five-fold. Logistic Regression is used for prediction. Lately, GridSearchCV has been used for hyperparameter tuning. Lastly, the model is saved and deployed using Streamlit.
