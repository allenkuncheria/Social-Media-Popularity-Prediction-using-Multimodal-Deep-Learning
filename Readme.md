# Title
Social Media Popularity Prediction Using Multimodal Deep Learning

# Description
My Master's thesis involved proposing a deep learning model for social media popularity prediction by optimising a state-of-the-art method for inference latency and number of parameters. The proposed model was evaluated for accuracy and resource-efficiency and compared with the base model.

This repository contains the code files used to carry out the research project.

# Contents
The code files include 5 Jupyter notebooks and are as follows.
1. Social Features.ipynb - This file contains the code for data preprocessing, exploratory data analysis, feature engineering and sampling of social features. Samples of 20% and 40% of the data were generated and saved for further processing.


2. Image Features.ipynb - This file contains the code for data preprocessing, exploratory data analysis, feature engineering and sampling of image features for both the VSCNN and Modified VSCNN models. Exploratory data analysis was carried on the images corresponding to the 40% sample, but VGG-19 and MobileNetV2 features were generated for the 20% sample. Inference lateny of image feature generation was also calculated in this code file.


3. VSCNN Model.ipynb - This file contains the dimensionality reduction, modelling and evaluation steps of the VSCNN model on the 20% sample of the data.

4. Modified VSCNN Model.ipynb - This file contains the dimensionality reduction, modelling and evaluation steps of the Modified VSCNN model on the 20% sample of the data.


5. Inference Latency.ipynb - This code file was used to calculate the inference latency of data preprocessing and feature extraction of social features.

# Caveat
The experiments were carried out iteratively and the results were noted after each step. Samples of 20% and 40% of the data were both generated and experimented upon and the 20% sample was finalised. As a result, the code files may show results from different experiments, but only those of the 20% sample were reported in the Master's thesis.