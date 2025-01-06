# Supervised--mini-project-classification
This project is a machine learning application that uses the Breast Cancer  dataset to classify whether a tumor is malignant or benign based on various features.

# Loading and preprocessing:
1. import the necessary modules and libraries:
     pandas
     numpy
     seaborn
     matplotlib
     train_test_split
     StandardScaler
     KNeighborsClassifier
     LogisticRegression
     accuracy_score,classification_report,confusion_matrix,mean_absolute_error,r2_score,mean_squared_error,precision_score,recall_score,f1_score
2. Load the dataset and Preprocess the data to handle any missing values and performed necessary feature scaling.
    Data preprocessing:- Finding the total rows and columns by using info(). Isnull() is used to find any null values are there. And using fillna() is used to replace the missing values.
                         describe() is used to get the statistics from the dataset. duplicate() is used for finding duplicate values.
                         By using boxplot we find out any outliers in the data and skew() is used to find out the skewness of the data.IQR method is used to remove outliers from the data.
                         
3. Classification Algorithm Implementation and find the accuracy of models.
      1. Logistic Regression 
      2. Decision Tree Classifier
      3. Random Forest Classifier
      4. Support Vector Machine (SVM)
      5. k-Nearest Neighbors (k-NN
  
4.From the above we can conclude that the best model is Support vector machine and the worst one is Decision tree
