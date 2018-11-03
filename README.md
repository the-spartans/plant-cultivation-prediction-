# plant-cultivation-prediction-

MODULE TO PREDICT THE SUITABLE MONTH FOR PLANT CULTIVATION
This module is to help farmers predict the suitable months to cultivate a particular crop in a particular region. 

DATASET:
The dataset has the columns city name, season, crop, average rainfall required for the crop, and the months suitable for cultivation. The factors considered for prediction are ‘season’ and ‘crop’ and the factor being predicted is ‘preferable month’. These data are collected from various datasets available from the Meteorological department of India and from the Agricultural department of India. The average rainfall for the district is calculated as part of the dataset. 

ALGORITHM:
The x label and y label parameters of the dataset are defined. The string parameters are encoded first using label encoding and one hot encoding. The encoded dataset is then split using the data split function. The data is split in 7:3 ratios for the training set and the test set. The model is trained using the training set and the prediction is done for the test set. The accuracy of the prediction is calculated and the confusion matrix is displayed.              
