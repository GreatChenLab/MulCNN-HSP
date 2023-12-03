# MulCNN-HSP
MulCNN-HSP: A multi-scale convolutional neural networks-based deep learning method for classification of heat shock proteins 
![image](https://github.com/GreatChenLab/MulCNN-HSP/assets/90399926/ebf33216-7b13-4434-90d2-93e03586fedc)
## Introduction to MulCNN-HSP
The multi-scale convolutional neural networks-based deep learning model, called MulCNN-HSP, is proposed for the classification of heat shock proteins. Given a protein sequence, it is first encoded using one-hot encoding and then fed into the multi-scale convolution. After the convolution operation, we incorporate global max pooling and dropout layers. Ultimately, the input protein sequence will be classified through a fully connected layer.

## Must installed packages or softwares
Pandas==0.23.4

Numpy==1.19.0

Tensorflow==2.0.0

Skikit-learn==1.0.2

## Webserver
[http://cbcb.cdutcm.edu.cn/HSP/](http://cbcb.cdutcm.edu.cn/HSP/)

## Coda
1. train.ipynb is the model training for HSP identification and classification;
2. test.ipynb is the prediction of HSP identification and classification.
## Data
HSPs can be categorized into six families, i.e. HSP20, HSP40, HSP60, HSP70, HSP90, and HSP100. Different families of HSPs have distinct roles. Classification of HSP families is of great significance for accurately understanding their biological functions.
## Models
The file "model" contains the final model weights for the independent tests. 
1. hsp_model.h5 is the final model weight for HSP identification; 
2. hsp_class_model.h5 is the final model weight for HSP classification.
