# Ship Image Classification using Deep Learning
#### Ahsan Khan | 11-26-2024
##### [Github Repository](https://github.com/Ahsanakhan/CSCA-5642-Final-Project)

## Introduction
This project focuses on developing a deep learning model to classify different types of ships based on images. The task is part of a Deep Learning Hackathon organized by Analytics Vidhya, aiming to showcase the application of computer vision techniques in maritime domain awareness. In today's global maritime landscape, rapid and accurate ship identification is crucial for:
- Maritime security
- Port efficiency
- Environmental protection
- Trade monitoring
- Search and rescue operations

This project leverages deep learning to automate ship classification from visual data, addressing limitations of traditional manual and radio-based identification methods.

## Dataset Overview
- Source: **[Analytics Vidhya Deep Learning Hackathon](https://www.kaggle.com/datasets/arpitjain007/game-of-deep-learning-ship-datasets/code)**
- Contents: 6,252 training images and 2,680 test images
- Categories: 5 ship types (Cargo, Military, Carrier, Cruise, Tankers)
- Image format: Various sizes, RGB color

## Project Objective
The main objective is to develop and compare different deep learning models for accurate ship classification, ultimately selecting the best performing model for potential real-world applications.
## Methodology
1. **Data Loading and Initial Exploration:** We'll load our dataset using pandas and examine it's structure and do some initial exploration.
2. **Exploratory Data Analysis (EDA):** Next, we'll visualize the distribution of ship categories using a bar plot and display some sample images from each category to underatnd the image and we'll also analyze image dimensions and color modes.
3. **Data Preprocessing:** We'll do data preprocessing that'll include image resizing, data augmentatio, normalization and data splitting.
4. **Model Development:** We'll develop several models such as Simple CNN, Complx CNN, Transfer Learning with ResNet50 and Transfer Learning with MobileNetV2.
5. **Model Evaluation and Comparison:** We'll evaluate each model performace and compare their learning curves and test accuracies.
6. **Hyperparameter Tuning:** Then we'll utilize Keras Tuner to perform hyperparameter optimization on the best performing model.
7. **Results and Analysis:** In the end, we'll plot the final best hypertuned model and compare it's results with the original model.
8. **Conclusion and Discussion:** Then we'll conclude our project findings and discuss some future improvements.

