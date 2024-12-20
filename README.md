# High Dimensional and Deep Learning (HDDL) Mini Projects
INSA Toulouse

# Authors
* BUI Minh Thi
* NGUYEN Thanh Chung
* OPDAL Vilde 
* VAZQUEZ ARELLANO Laura Karina 

## Description

These projects aim to deepen the theoretical and practical knowledge acquired during lectures and lab sessions of HDDL class. Below are the details of the four mini-projects that form part of this coursework.

## Mini-projet n°1– Qui a peint ce tableau?
### Objective

Build and train a neural network capable of solving the Art Challenge task: "Who painted this painting?" using the dataset extracted from the challenge at Art Challenge.

### Dataset
The dataset consists of:

* artists.csv: Lists the artists considered for this project, including their birth and death years, a brief biography, their preferred painting style, the number of works studied, and a link to their Wikipedia page (in English).

* images_hq: High-definition images of paintings, categorized by artists.

* images_lq: Low-resolution versions of the same paintings.

## Mini-projet n°2: Conditional VAEs

### Objective

Define and train a Conditional Variational Autoencoder (CVAE) on the Fashion-MNIST dataset.

### Tasks

* Research CVAEs: Understand their differences from VAEs, their loss functions, and other key concepts.
* Train a CVAE using PyTorch.
* Generate five new samples for each class in Fashion-MNIST.

## Mini-projet n°3: SSL for Anomaly Detection

### Objective

Evaluate different self-supervised learning (SSL) strategies for anomaly detection.

### Datasets

* MVTec AD: Categories include bottle, hazelnut, capsule, toothbrush.
* AutoVI: Perform experiments only on the engine wiring category.

### Tasks

* Train at least three different SSL models (e.g., masked autoencoder, contrastive model, inpainting model, colorizing model, siamese network) using only normal training data.
* Use model loss as an anomaly score and evaluate its discriminative power via ROC curves and AUROC metrics.

## Mini-projet n°4: RNN, LSTM, and GRU vs MLP and CNN

### Objective

Compare RNN, LSTM, GRU, MLP, and CNN models on the IMDB dataset for sentiment analysis.

### Tasks

* Train the following models on the IMDB dataset:

  - RNN

  - LSTM

  - GRU

  - MLP

  - CNN (with 1D convolutions)

* Compare models based on:

  - Architecture choices (layers, sizes, activations).

  - Hyperparameters (batch size, learning rate, epochs, etc.).

  - Loss functions.

  - Time taken, memory footprint, and accuracy.

  - Implement an ensemble classifier using majority voting over the above models.

  - Evaluate improvements from ensembling.

  - Interpret the results.
 
  # Data Sharing Note
To prevent exceeding GitHub's storage limitations, we have created a shared Drive where all datasets and supplementary files used in these projects are uploaded. Link: https://drive.google.com/drive/folders/1N3MvZ60H9STzJMU3p3Ai1u33wwfLrobT?usp=drive_link 
