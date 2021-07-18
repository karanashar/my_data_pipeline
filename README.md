# my_data_pipeline
This is a generalized Machine Learning Pipeline for Classification tasks.
Any dataset can be processed via this pipeline. All one has to do is write code to pre-process the data. For example - Remove columns, Fill missing values etc.
An ensemble model is used to predict the final outcome. The threshold value is changed to maximize the difference between the true positive rate and false positive rate.
The base version uses Logistic Regression, Random Forest, Support Vector Machine and Gradient Boosting Classifier to contribute to the ensemble model.
New models can be added to the ensemble very easily.
