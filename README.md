# Prediction-Arabic-Numbers
Final Project Updated

 For my final project, I created a prediction method to predict the exact Arabic number from a picture or diagram. Using the abundance of data and pictures, I created predictions with upto 99.8% accuracy by using techniques such as Logistic Regeression, Bagging, and Random Forest.

My prediction consisted of seperating the pixel's in the photograph to try to find a pattern in each data point (picture), and therefore make a prediction based on the patterns. After creating a baseline accuracy, I attempted to find the most effective technique to help the prediction process. After a series of testing, the bagging classifier was the most accurate at 99.8%

However, some issues arose during the prediction process. Certain numbers seemed to be confused and predicted incorrectly, and this was due to the similarity in the number's structure. Thus, after creating a confusion matrix, I can see that the numbers 7 & 3 and 6 & 7 get predicted incorrectly at a higher rate than any other combination of numbers.
