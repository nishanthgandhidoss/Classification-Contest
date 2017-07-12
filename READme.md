# Classfication Contest

-	Performed pre-processing such as modifying column names, visualizing missing values using the missmap diagram.
-	Split the whole dataset into train and test to perform validation of the models generated.
-	Selected significant features using correlation, rank by importance and recursive feature elimination techniques to generate the model with few variables that can explain maximum variability and avoid overfitting.
-	Implemented 10-fold cross-validation techniques and calculated the accuracy, AUC to tune the parameters of the model.
-	Build following 7 classification models to predict the masking label using the median response time of selected features(Letters).
1.	Logistic Regression
2.	Naive Bayes
3.	K-nearest Neighbor
4.	Decision/partition Tree
5.	Random Forest
6.	SVM
7.	Neural Network
-	Generated an ensemble model by combining the output of all the above seven models to achieve 100% accuracy on the test dataset.
