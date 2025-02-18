# Garments Price Prediction

This repository contains code for predicting garment prices using deep learning models. The project includes four Jupyter notebooks, each configured for different conditions based on dataset type and image size.

## Dataset Information

The datasets can be found at the following link:
[Garments Dataset](https://drive.google.com/open?id=0B4wcTeTa5IeNcExhbS1iaXBGLTA)

The datasets are divided into two categories:
1. **Data with Background**
2. **Data Without Background**

Additionally, two separate sheets, **MAHATI corpus.xlsx** and **cotton.csv**, contain the corresponding labels.

## Installation & Setup

To run the Jupyter notebooks, ensure that both the datasets and notebooks are properly aligned based on your OS paths.

### Requirements:
- Install **Jupyter Kernel** by downloading **Anaconda 2.7**
- Install **TensorFlow-GPU** for enhanced neural network performance
- Install **Keras** for model creation

## Running the System

The repository includes the following Jupyter notebooks:

1. **final_with_back.ipynb** - Images with background, resized to **30x30**
2. **final_with_back_50x50.ipynb** - Images with background, resized to **50x50**
3. **final_without_back.ipynb** - Images without background, resized to **30x30**
4. **final_without_back_50x50.ipynb** - Images without background, resized to **50x50**

## Model Workflow

1. Images are loaded and resized using an antialiasing approach.
2. The images are passed through a **Keras-based** neural network.
3. The neural network output is combined with meta-features from **MAHATI corpus.xlsx**.
4. The combined features are fed into a **Support Vector Regression (SVR)** model.
5. The final prediction is obtained, and accuracy is evaluated using **Mean-Square-Error-Percentage**.

## Further Analysis

For an in-depth analysis, refer to the **project report**.

---

Thank You.

