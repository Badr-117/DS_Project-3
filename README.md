# Introduction

In this project, our **goal** is to predict the type of physical activity (e.g., walking, climbing stairs) from tri-axial smartphone accelerometer data.

## Datasets description

We was given two input datasets, one to train our model, and the second one to test our model predictions. <br /><br />
*Training data*
- The input data used for training in this project consists of two files. The first file, **train_time_series.csv**, contains the raw accelerometer data, which has been collected using the Beiwe research platform, and it has the following format: **timestamp, UTC time, accuracy, x, y, z**

- The second file, **train_labels.csv**, contains the activity labels, and we'll be using these labels to train your model. Different activities have been numbered with integers. The following encoding is used: 1 = standing, 2 = walking, 3 = stairs down, 4 = stairs up. Because the accelerometers are sampled at high frequency, the labels in train_labels.csv are only provided for every 10th observation in train_time_series.csv.

*Testing data*
- The input data used for testing also consists of two files **test_time_series.csv** and **test_labels.csv** which both have the same structure as the training data. This file **test_labels.csv** only contains the time stamps needed for prediction, and we will need to augment this file by adding the corresponding class predictions (1,2,3,4)

## Key steps

1. Data Preprocessing (Data cleaning, Initial data transformation)

2. Data Visualization/analysis

3. Data Processing (Balancing data, Feature engineering)

4. Model training & evaluation (using accuracy)

5. Testing data classification 
