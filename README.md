# Predicting which character is speaking based on dialogue 
Use the text from training dataset to predict testing dataset
# Requirements
Python >=3.0<br />
Tensorflow >=2.0<br />
Numpy <br/>
GPU P100 <br/>
# Pretraining
read.csv :read dataset<br />
brief_cleaning: remove non-alphabetic characters
preprocessing.LabelEncoder :convert labels to vector<br />
vocab_file : build a vocabulary file
# Training
Parameters: <br />
validation_split<br />
epochs: times of iteration <br />
batch_size: size of batch being trained
# Running



# References
https://www.kaggle.com/code/nayansakhiya/text-classification-using-bert/notebook
https://www.kaggle.com/code/foolofatook/news-classification-using-bert
