# Covid19 Prediction and Analysis

## Introduction


- This project is divided into 2 parts
  1. Pneumonia detection from lung x-rays: COVID19 virus affects the respiratory system of healthy individual & Chest X-Ray is one of the important imaging methods      to identify Pneumonia caused due to corona virus. With the Chest X - Ray dataset, developed a Deep Learning Model to classify the X-Rays of Healthy vs              Pneumonia (Corona) affected patients.
  2. Monitoring the progress of Vaccination: Monitoring and comparing and forecasting the progress of Vaccination with the COVID19 cases per day.

- This model also powers a web application to classify the Corona Virus (Pneumonia) X-rays.


## Datasets Used



## X-RAY CLASSIFICATION
Classification Model:
¡ Input Data :
80-20 split
Augmented - rescale the image 1./255, rotate by 90 degrees, shift width and height by 0.15,flip horizontally, zoom by 0.5.
¡ Convolutional neural network :
4 Conv layers with 3x3 strides, ReLU Non-Linearity , Max Pooling, Batch Normalization 4 Dense Layers with Dropout
Softmax layer
