# Homework 4
> Comparative Analysis of Vision Transformer and SWIN Models for Image Classification

## Table of contents
* [Introduction](#Introduction)
* [Dataset](#Dataset)
* [Model](#Model)
*  [Results](#Results)
* [Code](#Code)

## Introduction

To implement and compare the performance of Vision Transformer (ViT) and Swin Transformer models on the CIFAR-10 dataset for object classification, and to analyze their decision-making processes using Grad-CAM visualization.


## Dataset
The dataset used is CIFAR-10 (60,000 images, 10 classes) via PyTorch torchvision.datasets.CIFAR10.
 
## Model

We Fine-Tune with two models:

1.   **Vision Transformer (ViT):**  vit_base_patch32_224 from timm.

2.   **Swin Transformer:**  swin_base_patch4_window7_224 from timm.


## Results

Lets look at the graphs for a better understanding of the models.

1.  Accuracy and Loss Curve for ViT Head only Fine-Tune 
![ViT_Head](https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-4/Graphs/ViT_Head.png)

	Confusion Matrix for ViT Head only Fine-Tune
![ViT_Head_cm](https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-4/Graphs/ViT%20Head_cm.png)
2. Accuracy and Loss Curve for ViT Full Fine-Tune  
![Vit_Full](https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-4/Graphs/ViT_Full.png)
Confusion Matrix for ViT Full Fine-Tune
![ViT_full_cm](https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-4/Graphs/ViT%20Full_cm.png)

3. Accuracy and Loss Curve for SWIN Head only Fine-Tune  
![Swin_head](https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-4/Graphs/SWIN_Head.png)
Confusion Matrix for SWIN Head only Fine-Tune
![Swin_head_cm](https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-4/Graphs/SWIN%20Head_cm.png)

## Code 
You can check the jupyter notebook (.ipynb file) for the code

<a href="https://github.com/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-4/Code/RNN_HW4.ipynb" target="_blank">
  <img 
    src="https://cdn-icons-png.flaticon.com/512/10817/10817310.png" 
    alt="Code Icon" 
    width="20"
    style="vertical-align: middle; margin-right: 5px;"
  />  Jupyter notebook
</a> <br><br>
You can also run the code on collab 
<a target="_blank" href="https://colab.research.google.com/github/Lonelypheonix/Recurrent_Neural_Network-NYCU/blob/main/Homework-4/Code/RNN_HW4.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
