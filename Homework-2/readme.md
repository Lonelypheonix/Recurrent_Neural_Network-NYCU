# Homework 2
> Classifying Disaster Tweets Using LSTM and GRU

## Table of contents
* [Introduction](#Introduction)
* [Dataset](#Dataset)
* [Model](#Model)
*  [Results](#Results)
* [Code](#Code)

## Introduction

The objective of this project involves classifying tweets to determine whether they are about a real disaster or not. We explore two types of recurrent neural networks (RNNs) for this task:



## Dataset

The <a href="https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-2/Dataset/train.csv" target="_blank">"**train.csv**"</a>  file is a dataset obtained from Kaggle includes tweet texts and a target label indicating whether the tweet is about a real disaster.
-  **1** for real disaster.  
-  **0** for not a real disaster.

**Shape of the Training Dataset**:

-   Rows: 7613
-   Columns: 5 (id, keyword, location, text, target)

**Initial Observations**:

-   Each row represents one tweet.
- The target column is the class label (0 or 1).

The <a href="https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-2/Dataset/test.csv" target="_blank">"**test.csv**"</a>  file is a dataset obtained from Kaggle includes tweet texts and we have to predict the target label indicating whether the tweet is about a real disaster.
**Shape of the Testing Dataset**:

-   Rows: 3264
-   Columns: 4 (id, keyword, location, text)

For details of the dataset, see the Kaggle website:
https://www.kaggle.com/competitions/nlp-getting-started/overview

## Model

We experimented with two neural network architectures:

1.  A LSTM (Long Short-Term Memory) model

2. A GRU (Gated Recurrent Unit) model

## Results

Lets look at the graphs for a better understanding of the models.

1.  Accuracy
![Accuracy](https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-2/Images/Accuracy.png)

2. Loss
![Loss](https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-2/Images/Loss.png)

3. Kaggle Submission
![Kaggle](https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-2/Images/kaggle_submission.png)

4. Model Prediction 
The results are saved in <a href="https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-2/Predictions/prediction_results.csv" target="_blank">
   "prediction_results.csv"
</a> 
## Code 
You can check the jupyter notebook (.ipynb file) for the code
<a href="https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-2/RNN_HW2.ipynb" target="_blank">
  <img 
    src="https://cdn-icons-png.flaticon.com/512/10817/10817310.png" 
    alt="Code Icon" 
    width="20"
    style="vertical-align: middle; margin-right: 5px;"
  />  Jupyter notebook
</a>
You can also run the code on collab 
<a target="_blank" href="https://colab.research.google.com/github/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-2/RNN_HW2.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>


