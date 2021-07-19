# My data pipeline - Classification
<p>This is a generalized Machine Learning Pipeline for <br>Classification tasks</br>.
Any dataset can be processed via this pipeline.<br> All one has to do is write code to pre-process the data. For example - Remove columns, Fill missing values etc.
  <br> <b>Note</b> - The pipeline is mainly intended to work for datasets with numerical and binary features only. Categorical features can be handled using some extra effort 

<p>An ensemble model is used to predict the final outcome. The threshold value is changed to maximize the difference between the true positive rate and false positive rate.
<br>The base version uses Logistic Regression, Random Forest, Support Vector Machine and Gradient Boosting Classifier to contribute to the ensemble model.
<br>Customization options are available to add new models and try new parameters for them. New scalers can also be added.<br>New models can be added to the ensemble very easily.
