# heartriskprediction
Used machine learning algorithms to identify people with risk of heart disease based on their past and current health conditions. 
Data was taken from kaggle. 
Target variable (having heart disease) contains severe class imbalance.
91% of the people in the dataset do not have heart disease, so if the models predicted 
that everyone did not have heart disease, they would be right 91% of the time. Using F1 
score and recall metrics instead of accuracy will allow to account for the large 
number of false negatives that will come with the imbalance. 
SMOTE is used (synthetic minority oversampling technique) to account for the 
imbalance in the dataset, and it improved the metrics for recall tremendously. Oversampling is used 
instead under sampling since it provided better metrics and also to avoid drastically decreasing the data size. 
