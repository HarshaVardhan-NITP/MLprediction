*********Welcome to the project Machine Learning Prediction of Titanic incident suvivors*********

* First the program for prediction is written in jupyter notebook. Which is an interface for visualisation and analysis purposes.

* Used Data Analysis libraries like Numpy,pandas

* Used libraries for algorithm will be provided in sklearn, and for visualisation we use seaborn and matplotlib.

* import your train.csv file into pandas dataframe.

* first we preprocess the data by removing any Not a number values(Nan) are found or replacing male and female to 0 and 1.

* next we corelate each and every feature to all others, we take the mostly corelated features for out data set.  

* We created dummies for categorical data like (0's and 1's) in the new dataset with including the main dataframe containing data of train.csv file.

* We normalized the data and feeded the data into input(x) and output(y) variables where 'y' is is the specific person survived or not.

* After we feeded the data with needed features in x and y.

* We use different algorithms like K Nearest Neighbors, Random Forests, Svm , Logistic Regression .

* Out of those algorithms accuracy which is calculated by cross_val_score method is more we take that algo and use for future prediction on test.csv file.

* After the importing of test.csv file into data frame and use the algorithm which we trained earlier with training data with more accuracy(K nearest neighbors)in my case to predict the
Predictions.

                                                      *****This data set is from kaggle competition******
									****Thank You*****



 