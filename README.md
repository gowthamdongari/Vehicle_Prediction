# Vehicle_Prediction
detecting the Vehicles passing on a highway based on the readings of a detector
we are provided with a sample that represents our data which is very less to perform any operation and come up with a model
Understanding the data as how many readings are recorded if a vehicle is passing through the metal strip, Given the small sample the avg reading for each vehicle is well differentiated, So considered the 6 Sigma level approach by finding the upper and lower boundary by observing mean and standard deviation for vehicle types.
Then we calculate the -3 and +3 sigma levels and use this for predicting the accuracy, i.e 99%

To build a Machine Learning Model Creating a data resembling our sample and we build a machine learning model on it
creating the data considering the average lengths of bike (1.8m), car(4.5m), & bus-(14m) given the speed of the vehicles is 15 kmph i.e is 4.1666 m/s, we calculated the average time taken for the vehicles to cover its own length
now we create a dataset accordingly and created new Polynomial Features and moving average to predict the vehicle Using Random Forest Classifier.
