# Liver Fibrosis Classification using ResNet with CBAM

This project aims to classify the stage of liver fibrosis from histopathology and ultrasound images using a deep learning model. The model used is a ResNet architecture modified with a Convolutional Block Attention Module (CBAM) to improve classification accuracy.

## Dataset

The dataset used in this project is the "Liver Histopathology Fibrosis Ultrasound Images" available on Kaggle. This dataset contains 6323 images divided into several classes based on the fibrosis stage.

- **Dataset Source:** [Liver Histopathology Fibrosis Ultrasound Images](https://www.kaggle.com/datasets/vibhingupta028/liver-histopathology-fibrosis-ultrasound-images)
- **Total Images:** 6323
- **Training Set:** 5058 images
- **Testing Set:** 1265 images

## Model

The model architecture used is **ResNet (Residual Network)**, which has proven effective in various image classification tasks. To further enhance performance, this model is integrated with a **Convolutional Block Attention Module (CBAM)**. CBAM is an attention mechanism that helps the model to focus more on important features within an image, both spatially and channel-wise, thereby increasing classification accuracy.

## Requirements

To run this notebook, you will need the following Python libraries:

-   os
-   seaborn
-   matplotlib
-   numpy
-   pandas
-   scikit-learn
-   tensorflow
-   keras
-   kagglehub

You can install all the required libraries using pip:

```bash
pip install seaborn matplotlib numpy pandas scikit-learn tensorflow keras kagglehub