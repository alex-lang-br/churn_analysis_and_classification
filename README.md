
# Welcome to this churn classification on a telecommunications business data set.

## The goal of this project was to see why customers decide to leave their service providers. The data comes from kaggle (https://www.kaggle.com/datasets/shilongzhuang/telecom-customer-churn-by-maven-analytics) and contains 7000 rows with 38 columns.
## We first do some EDA and data visualization to get a feel of our data (what's in it, what are the data type and do we need to convert them, and so on). The visualizations helped us understand our data set better; we were able to see the trend of the price in relation to the duration of a contract, as well as where most of the clients are located
## For the feature engineering, I converted every data types to numerical values, except for the 'City' columns, for which I decided to use LabelEncoding from sklearn (one-hot encoding would make our data too big for training the model). Finally, after scaling it with StandardScaler, we split the data into a 80/20 training and testing set. Our target is the customer status, i.e whether the customer churned or not.
## I used a Logistic regression since this was a binary classification
