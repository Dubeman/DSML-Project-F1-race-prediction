
# F1 Race Prediction

My pursuit is to develop a machine learning model to determine the features that contribute the most to victory of a driver in a Formula 1 race.These selected features would contribute the most in estimation the likelihood of a certain driver to win a Grand Prix. The driver with the most likelihood according to an appropriate classification model, utilising these particular selected features, would be mapped as the winner. After which, i can test the performance of my feature selection on a labelled data set which in my case, is the training data.

## Data description
All data available in the [Datasets](https://github.com/Dubeman/Datasets) repository.

The training data file contains the F1 data of races from 1983 to 2019 except for the data of 1998 season and the 2012 season. The excluded data (season 1998,2012) forms the test data which is unlabelled, for which i will reproduce the labels.The features are a mix of Categorical, Boolean ,integer and continuous variables which were further encoded through one hot encoding and label encoding. After encoding and further pre-processing by checking for missing data (none), dealing with negative values, I ended up with 98 columns which will serve as my features and 13,475 rows which are my training instances. The class labels (y train) are integers from 1 to 27 which represent the position on the podium for a particular driver after a particular race. 


## Tasks at hand :-

(i) An assortment of highly important features for prediction and an analysis of the same.

(ii)A classification model for prediction and an analysis of the same.

(iii) Generation of labels.

(iv) The prediction of the Winner(1st) for each round in each season.


## 🛠 Skills
Python 3


