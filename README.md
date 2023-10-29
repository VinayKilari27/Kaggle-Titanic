# Kaggle-Titanic
Exploring the Titanic Dataset
Introduction: This is the introductory Kaggle Challenge that I have done where we were given a dataset of the Passenger details who boarded the Titanic.
Objective: Our objective is to predict those who have survived or not by building a model.
The Preprocessing Steps: First comes the data preprocessing steps in order to get high accuracy such as Feature Identifying where we unselect the attributes who have high correlation, also some of those which doesn’t have high impact on the outcome which can be identified by using a Heatmap.
Hence, I have dropped the columns ‘Cabin’, ‘Name’, ‘Embarked’, ‘Ticket’ from the dataset
Dataset Splitting: Then comes the Test_Train_Split function which is used to split the dataset into four sub-datasets i.e “X_Train, X_Test, Y_Train, Y_Test” which in return is used to avoid the Overfitting issue and also facilitates in yielding high accuracy!
Model: I’ve chosen Logistic Regression to classify the outcomes for this dataset because it is quick, efficient and particularly well-suited for binary classification tasks.
Predicting Values: Using the predict() function, we can predict the “Survived” column.
Accuracy: The accuracy of this model is obtained by using the function accuracy_score() and have obtained a score of 81.6% for the above model.
