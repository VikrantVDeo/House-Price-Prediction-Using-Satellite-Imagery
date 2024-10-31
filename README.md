# House Price Prediction Using Satellite Imagery 

This repository contains an end-to-end pipeline for predicting house prices using satellite imagery from Google Earth's Landsat, leveraging both Computer Vision and Machine Learning (ML) techniques. The project combines image processing, feature extraction, and regression modeling to develop an efficient predictive system with high accuracy.

### Project Overview
This project aims to predict house prices by processing and analyzing satellite imagery data. Using Copernicus and Landsat imagery, we applied advanced computer vision techniques to detect and annotate key property features, which then informed our ML-based regression models.

### Pipeline Highlights
- **Data Pipeline**: We developed an ML pipeline that integrates computer vision, data augmentation, and data transformation to transform raw imagery into a format ready for regression.
- **Feature Extraction**: Using **YOLOv8** trained on a custom dataset of Landsat satellite images, we extracted meaningful features from each property, converting them into structured data for predictive analysis.
- **Regression Models**: After feature extraction, various regression algorithms were implemented to predict house prices:
  - Linear Regression
  - Gradient Boosting Regression
  - Random Forest Regression
  - K-Nearest Neighbors Regression
- **Performance Optimization**: With hyperparameter tuning and optimized transformations, the model achieved a **91% accuracy** in feature detection and **97% accuracy** in house price prediction.

### Key Technologies
- **Computer Vision**: YOLOv8, OpenCV, and custom preprocessing for feature extraction from satellite imagery
- **ML Models**: Scikit-Learn for model implementation and evaluation
- **Satellite Data**: Leveraging high-resolution **Google Earth Landsat Imagery** for training data

### Usage
This repository contains scripts for each step in the pipeline, including data preprocessing, model training, and prediction evaluation. 

### Results
Achieved 91% accuracy in object detection and 97% accuracy in predicting house prices, highlighting the potential of satellite imagery in real estate analytics.

