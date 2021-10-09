# Wine_Quality

In this project, I wanted to predict the quality of wine by training the data; I created two groups labelling them as "good" and "bad" and I set up bins to classify them into either of the groups. If the quality feature of the wine is between 7 and 8, it is labelled as "good" wine but if it is below 7, then it is labelled as "bad" wine. 

I then used Matplotlib and Seaborn to get a good picture of how much of the "good" and "bad" wine is present in the dataset(there are 1382 labelled to be 0 thus "bad" and 217 labelled to be 1 thus "good). 

The, I used the train_test_split package to split the data into testing and training data, keeping the test size to be 20% of the overall data. Since the values are also quite ranged with some very large and small values, I have used the Standard scaler package to fit and transform the data so we can get optimised results. 

Finally, I used the Random Forest Classification Model for the training and prediction using 200 forests. To see how well my model has performed at the end, I ran the classification report and the confusion matrix as well to compare the actualy y_test values with the predicted rfc_values. 


