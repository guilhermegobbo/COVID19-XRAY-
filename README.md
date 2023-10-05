# Pneumonia Detection in X-ray Images Project

This project is an implementation of a deep learning model to detect pneumonia in X-ray images of patients. The model uses a Convolutional Neural Network (CNN) architecture with three convolution layers to extract relevant features from the images and classify them as "Normal" or "Pneumonia."

## Project Overview

Early detection of pneumonia is crucial for effective treatment and patient recovery. This project utilizes deep learning techniques to automate the analysis of X-ray images and identify the presence of pneumonia.

## Neural Network Architecture

The CNN model used in this project consists of three convolution layers, followed by pooling layers and dense layers. The architecture is as follows:

1. Convolutional Layer with 32 filters, 3x3 kernel size, ReLU activation function.
2. Max Pooling Layer with a 2x2 pool size.
3. Convolutional Layer with 64 filters, 3x3 kernel size, ReLU activation function.
4. Max Pooling Layer with a 2x2 pool size.
5. Convolutional Layer with 128 filters, 3x3 kernel size, ReLU activation function.
6. Max Pooling Layer with a 2x2 pool size.
7. Dense layers followed by an output layer with sigmoid activation.

Obs.: On the 'pneumonia' and 'normal' folders are the data of test set. If you want to see all archives go to the link below.
The project can also be found at: [link to the Kaggle dataset](https://www.kaggle.com/datasets/khoongweihao/covid19-xray-dataset-train-test-sets)

![image](https://github.com/guilhermegobbo/covid-xray/assets/136920721/2d29eb0b-5179-4d8c-9419-866f6175c81e)
