# HEART_DISEASE
The dataset is taken from kaggle.The following model predicts whether a person has a healthy heart or no.
THe libraries are imported as and when required 
The data is a clean dataset thus it does not require any cleaning process.
The correlation can be seen in the heatmap.
Various values are predicted and represented in the bar graph.
the data is then split 
the  x_data drops the additional 2 columns which were created during the analyzation of age group and the chest pain type .it also drops the target variable
the y_data has only the target value
the data is then spilted using the train_test_split
the accuracy and confusion matrix using different models is calculated
#RANDOM_FOREST_CLASSIFIER turned out to be the most efficient model with the highest accuracy
