wisconsin breast cancer classification end-to-end ml model deployed through streamlit

Wisconsin dataset is in tabular form so it is easily to handle this type of dataset by using normal classification algorithms.

The algorithm used here is LogisticRegression and KNN,
LOGISTIC REGRESSION:
     Logistic regression estimates the probability of an event occurring, such as voted or didn't vote, based on a given dataset of independent variables. Since the outcome is a probability, the dependent variable is bounded between 0 and 1.
KNN:
     The k-nearest neighbors algorithm, also known as KNN or k-NN, is a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point.
     
 Before implementing any algorithm the dataset has to be splitted for training and testing.
 Then,the algorithm has to be implemented and at the end of completing a model should analyse the errors and accuracy of the model.
 
 The accuracy of the given test dataset shows 90%.
 
 The frontend of the model is deployed by using the python library called streamlit where it creates a dataframe using pandas and given a title for the UI.
 The model is predicted by giving if and else statement that comprises of two different variety of cancer one is malignant and the other is benign.
