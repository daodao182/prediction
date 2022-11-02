# The Simpsons
Predicting which character is speaking based on dialogue. 
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

# Keras API

```
lay = tf.keras.layers.Dense(64, activation='relu')(clf_output)
    lay = tf.keras.layers.Dropout(0.2)(lay)
    lay = tf.keras.layers.Dense(32, activation='relu')(lay)
    lay = tf.keras.layers.Dropout(0.2)(lay)
    out = tf.keras.layers.Dense(5, activation='softmax')(lay)
```

# Training
Parameters: <br />
validation_split<br />
epochs: times of iteration <br />
batch_size: size of batch being trained



# Running



# References
https://www.kaggle.com/code/nayansakhiya/text-classification-using-bert/notebook</br>
https://www.kaggle.com/code/foolofatook/news-classification-using-bert</br>
