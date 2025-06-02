# Human Activity Recognition using Convolutional Neural Networks
This is report about a Convolutional Neural Network (CNN)-based Human Activity Recognition (HAR) system using smartphone sensor data from the MotionSense dataset. The model processes accelerometer and attitude signals through a 1D CNN architecture, achieving 97\% test accuracy in classifying six activities: walking, jogging, sitting, standing, and ascending/descending stairs. Key pre-processing steps include sliding window segmentation and feature normalization. Results show near-perfect recognition for static activities (sitting, standing) and jogging, while stair related motions had greater challenges in classification. The report shows that CNNs can effectively extract spatal and temporal features for HAR, with potential applications in health monitoring, fitness tracking, and smart environments.

## Link to dataset
[MotionSenseDataset](https://github.com/mmalekzadeh/motion-sense)

## Structure
./src contains noteook with pre-processing, model and evaluation code  /
./report contains report with analysis of model performance

## Runnig
Place har.ipynb notebook in data folder
