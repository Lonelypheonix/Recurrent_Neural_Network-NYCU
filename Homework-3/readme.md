# Homework 3
> Develop a Named Entity Recognition (NER) tool based on BERT model.

## Table of contents
* [Introduction](#Introduction)
* [Dataset](#Dataset)
* [Model](#Model)
*  [Results](#Results)
* [Code](#Code)

## Introduction

The objective of this project is to develop a Named Entity Recognition (NER) tool based on BERT model. We explore two types of recurrent neural networks (RNNs) for this task:



## Dataset
The dataset used is Dataset for Named Entity Recognition in Threat Intelligence (DNRTI). it contains 13 entity types (e.g. EXP for exploit, HACKORG for hacking organization, TOOL, TIME, etc.) plus standard BIOES span markers.
The 13 categories in the data set are HackOrg, OffAct, SamFile, SecTeam, Tool, Time, Purp, Area, Idus, Org, Way, Exp, Features.

 - The <a
   href="https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/tree/main/Homework-3/Secbert-Pretrained/data/train.txt"
   target="_blank">"**train.txt**"</a>  file is used for Training  
   
 - The <a
   href="https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/tree/main/Homework-3/Secbert-Pretrained/data/valid.txt"
   target="_blank">"**valid.txt**"</a>  file is used for Validation
 - The <a
   href="https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/tree/main/Homework-3/Secbert-Pretrained/data/test.txt"
   target="_blank">"**test.txt**"</a>  file is used for Testing

## Model

We experimented with two neural network architectures:

1.  **Baseline BiLSTM-CRF**

2.  **SecBERT-BiLSTM-CRF**



## Results

Lets look at the graphs for a better understanding of the models.

1.  Loss Curve during Baseline Training 
![Baselineloss](https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-3/images/Baseline%20loss.png)

2. Loss Curve during SecBert Training 
![SecbertLoss](https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-3/images/secbert%20loss.png)

3. F1 Score During SecBert Training 
![F1](https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-3/images/secbert%20f1.png)

4. Model Prediction 
The SecBert results are saved in <a href="https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-3/Secbert-Pretrained/model_output/test_results.txt" target="_blank"> "test_results.txt" </a> 

## Code 
You can check the jupyter notebook (.ipynb file) for the code
Baseline BiLSTM
<a href="https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-3/Baseline/baseline.ipynb" target="_blank">
  <img 
    src="https://cdn-icons-png.flaticon.com/512/10817/10817310.png" 
    alt="Code Icon" 
    width="20"
    style="vertical-align: middle; margin-right: 5px;"
  />  Jupyter notebook
</a>
You can also run the code on collab 
<a target="_blank" href="https://colab.research.google.com/github/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-3/Baseline/baseline.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

SecBert BiLSTM-CRF
<a href="https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-3/Secbert-Pretrained/Secbert-Pretrained.ipynb" target="_blank">
  <img 
    src="https://cdn-icons-png.flaticon.com/512/10817/10817310.png" 
    alt="Code Icon" 
    width="20"
    style="vertical-align: middle; margin-right: 5px;"
  />  Jupyter notebook
</a>
You can also run the code on collab 
<a target="_blank" href="https://colab.research.google.com/github/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-3/Secbert-Pretrained/Secbert-Pretrained.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

