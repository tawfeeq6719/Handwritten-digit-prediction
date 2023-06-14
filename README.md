# Handwritten-digit-prediction

Explanation:

1.The code begins by importing the necessary libraries and loading the "load_digits" dataset. The dataset is then visualized using matplotlib.

2.Next, the data is preprocessed by reshaping the images and scaling the pixel values. The target variable (y) and feature variables (X) are defined.

3.The data is split into training and testing sets using the train_test_split function.

4.A Random Forest Classifier model is created and trained using the training data.

5.The model is evaluated by predicting the digits for the test data and calculating the confusion matrix and classification report.

6.Finally, the model can be used for prediction on new handwritten digits by providing the new data to the trained model.
