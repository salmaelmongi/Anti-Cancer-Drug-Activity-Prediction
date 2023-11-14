# Anti-Cancer-Drug-Activity-Prediction

## Overview:


This repository contains code for predicting anticancer activity using Graph Neural Networks (GNNs). The task involves classifying chemical compounds based on their graph representations, where atoms represent nodes and bonds represent edges. The prediction task is to determine whether a compound is positive against non-small cell lung cancer.

## Dataset:


The dataset consists of chemical compounds represented as graphs. Each compound's structure is saved as a Structure Data File (SDF), where atoms represent nodes and bonds as edges. Compounds are labeled as positive or negative against non-small cell lung cancer.

## Methodology:


GNN Architectures
This project explores various GNN architectures for the anticancer activity prediction task:

GGNN (Gated Graph Neural Network)
RGCN (Relational Graph Convolutional Network)
RGAT (Relational Graph Attention Network)
RGIN (Relational Graph Isomorphism Network)
GNN_Edge_MLP (Edge-wise Multi-Layer Perceptron)
GNN_FiLM (Feature-wise Linear Modulation)
Each GNN architecture has its unique approach to message passing and graph structure analysis. Hyperparameter tuning and evaluation metrics differ across these architectures.

## Model Training:


Training Process
The models are trained using TensorFlow and Keras.
Training is performed on a subset of the data using various GNN architectures.
Hyperparameters are tuned via grid search and cross-validation techniques.
Evaluation Metrics


## Evaluation metrics include:


Accuracy
Area Under the ROC Curve (AUC)
Loss (Binary Cross Entropy)
