# Urban-Green-Cover-Image-Assessment

## Project Overview

This project aims to assess urban green cover using satellite imagery from the EuroSAT dataset. A custom Convolutional Neural Network (CNN) and a MobileNetV2 transfer learning model are developed and compared for land-cover classification.

## Dataset

Dataset: EuroSAT RGB

Dataset Link:
https://www.kaggle.com/datasets/apollo2506/eurosat-dataset

Number of Images: 27,000

Number of Classes: 10

Classes:

* AnnualCrop
* Forest
* HerbaceousVegetation
* Highway
* Industrial
* Pasture
* PermanentCrop
* Residential
* River
* SeaLake

## Technologies Used

* Python
* TensorFlow/Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn

## Models Implemented

### Custom CNN

* Conv2D
* MaxPooling
* Dense Layers
* Dropout

### MobileNetV2 Transfer Learning

* Pretrained ImageNet Weights
* Global Average Pooling
* Dense Classification Layer

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## Output Figures

* Class Distribution
* Accuracy Curves
* Loss Curves
* Confusion Matrix
* Model Comparison

## How to Run

1. Open the Kaggle notebook.
2. Attach the EuroSAT dataset.
3. Run all notebook cells.
4. Generated figures will be stored in outputs/figures.

## Results

The project compares the performance of a custom CNN and MobileNetV2 transfer learning model for urban green cover assessment using satellite imagery.
