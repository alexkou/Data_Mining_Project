## A. Healthcare stroke dataset
- Visualize the dataset
- Handle missing values with the following methods
  *   Remove columns with missing values
  *   Fill numerical missing values with the average of the column
  *   Fill numerical missing values using Linear Regression
  *   Fill categorical missing values using KNN
  *   Combine Linear Regression and KNN

- For every dataframe, predict whether or not a patient is prone to having a stroke using **Random Forest Classifier** by splitting the dataset into training-test with a ratio of **75%-25%** and evaluate the performance of the model using **F1-score, precision and recall**. Next, try to improve the results by experimenting with the hyperparameters.


## B. Spam or not spam dataset
Predict whether an email is spam or not using neural network. With the following steps we achieved a percentage of **97%** across all metrics.
- Convert text into numbers
- Create our own Embedding Layer
- Split training-test data with a ratio of 75-25%
- Train a dense neural network model and fit it for 10 epochs.
