### Airline Passenger Satisfaction Score Classification

##### Goal of this project:¶
Customer satisfaction analysis is a crucial step for businesses to reflect and improve their service quality. In this project, we are going to study the airline passenger satisfaction based on features related to the passengers, airline services, and other features. We will use different machine learning models to train our dataset, then evaluate the performances on testing data using confusion matrix. We could also look at factors that will impact customers' satisfaction ratings and provided some suggestions to airline businesses.

##### About this Dataset:
This dataset is found on Kaggle, which contains a training file and a testing file. The training data has 103904 rows (80%) and 24 columns, and the testing data has 25976 rows (20%) and 24 columns. Here, I hope to do cross-validation for classification, so I will combine the two files together. Due to a large amount of data and slow computing power issues, I decided to pull only 20,000 data and do the classification. However, it would be simple to change it back to the full data set anytime if we want to use all the data because using only a subset of data might make our data not complete or not representative. However, our data analysis and visualization will still work on the full dataset.

Data: https://www.kaggle.com/teejmahal20/airline-passenger-satisfaction
