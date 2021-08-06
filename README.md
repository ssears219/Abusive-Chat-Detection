# Abusive Chat Detection

Using machine learning to detect hate speech, offenive messages, and profanity in the chat space.

![Angry](https://cdn.pixabay.com/photo/2020/10/14/20/30/angry-5655418_960_720.png?raw=true)

## Description

In this project, labeled tweets are examined to find associations between words in the tweets 
and hate or offensive language. The data sets are then processed and vectorized as a means to create 
machine learning models that predict whether or not a message contains hate speech or offensive 
language. The models are then used in addition to a list of profane words to create a pipeline for 
screening messages for inappropriate language. The pipeline is then tested on a labeled random sample 
from a customer service chat data set. Finally, a use case for this service is explained for the customer 
service chat domain.

## Data

[Labeled Tweet Data](https://www.kaggle.com/arashnic/7-nlp-tasks-with-tweets)
[Bitext’s Customer Support Dataset](https://blog.bitext.com/free-customer-support-dataset)

## Contents

Data  
Final Datasets - Contains final datasets used for modeling  
Raw Data - Raw datasets straight from the source  

Saved Models - Contains hate speech model and offensive speech model saved using PyCaret

Exploratory Data Analysis.ipynb - Initial loading of data, word clouds  
Predictive Modeling.ipynb - Data preprocessing, modeling prep, modeling, evalatuation, use case illustration  

Report.pdf - Comprehensive technical report on the project



## Tools
* Python
* PyCaret
* Sklearn
* Seaborn
* Wordcloud


## Authors

Samuel Sears @ssears219  


## Acknowledgments

* [Word Cloud](https://www.geeksforgeeks.org/generating-word-cloud-python/)
