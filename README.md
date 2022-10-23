# Emotion_and_Gender_Detection
In this project, our goal is to implement supervised and unsupervised methods to 
classify or cluster our data. The dataset we are using in this project is a set of 
voices from different ages, genders, and emotions. The goal is to determine each 
voice record's gender, emotion, and also in some cases, the different sentences
that are in each record. 
To implement a model for such a dataset, the first and the most important step is 
to implement a noise reduction on our dataset. After noise removal, we have to 
do some preprocessing on our data to prepare data for classification. In 
preprocessing step, first, we would calculate the Fourier transformation to
simplify our data and be able to extract features from the data. The next step is to 
normalize our data. This step is used for changing our features to the same scale 
so that all features would affect the result in the same weight. 
After Normalization, we can now start the main process which is feature 
extraction and feature selection. After selecting the best features for training data,
we can now split our data into train and test data and use supervised and 
unsupervised methods to classify or cluster our data. 
At last, we examine the quality of each model and with the use of metrics, we can 
determine the accuracy or other metrics used for measuring our model such as 
ROC table or confusion metrics to verify our models. At last, we will compare all 
these methods and define which algorithm works better for this dataset.
