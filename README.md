# Fire Detection Using Convolutional Neural Networks

## About the Project

This project aims to create a simple convolutional to perform the task of binary classification of images. The images are divided into the two classes 'Fire' and 'Non-Fire' and contains images mostly of rainforest fires and forests respectviely. The project was made in a single Jupyter Notebook that encompasses the sections of:
- Data Loading, 
- Preprocessing, 
- Model Training and 
- Evaluation.

The data loading section was done using TensorFlow Datasets, a different approach than the I was used to (i.e. using pandas Dataframes to load the data).

The final results can be found with more details displayed in the "Evaluations" section inside with the jupyter notebook. The following metric was achieved in the validation set:

- **Accuracy:**

## Goals

My main goal while I was making this project was to exercise concepts os Neural Networks and Computer Vision. I also aimed to fully understand all the process to gather and process the data, training a CNN model and evaluate it.

Also I tried to make the visualizations of the evaluation of the model the more intuitive and easy to understand as possible. It was very challenging but I was very pround of the results.

## Dataset Utilized
FIRE Dataset found on Kaggle: (https://www.kaggle.com/datasets/phylake1337/fire-dataset/data)

## Stack Utilized
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

## Acknowledges

- This project was heavely inspired by Nicholas Renotte "Build a Deep CNN Image Classifier with ANY Images" video (https://www.youtube.com/watch?v=jztwpsIzEGc&t=4364s)

- The CNN architecture was inspired by Pavan Sanagapati "A Simple CNN Model Beginner Guide !!!!!!" Kaggle Notebook (https://www.kaggle.com/code/pavansanagapati/a-simple-cnn-model-beginner-guide)

- The frame_image function was made with help from the solution found in the StackOverflow question "Adding a border to and Image in my code" (https://stackoverflow.com/questions/43261338/adding-a-border-to-and-image-in-my-code)