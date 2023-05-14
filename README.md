# jetson_nano_project
The study on plant disease detection using Convolutional Neural Networks (CNN), especially potato, seeks to build an automated system that can accurately identify illnesses in potato crops. This system analyses photos of potato leaves to categorise them as healthy or unhealthy using CNN, a deep learning approach. The identification of plant diseases using computer vision and deep learning techniques has the potential to revolutionise the agriculture business by providing early disease diagnosis and crop loss prevention.
# Dataset
The dataset used for this project is the https://www.kaggle.com/datasets/emmarex/plantdisease from kaggle. The dataset contains leaf images of tomato, pepper, and potato. This images are futher classified into early blight, late blight and healthy.
# Requirements
* To run this project, you will need the following:
* Python 3
* Tensorflow 2
* Keras
* OpenCV
* Numpy
* Scikit-learn
* Matplotlib
# Usage
* Download the dataset from Kaggle (https://www.kaggle.com/datasets/emmarex/plantdisease) and extract it to the dataset folder.
* Import the required libraries.
* Visualize and clean the dataset.
* Pre-process the dataset (Resize and rescale the image) 
* The plant_disease.h5 file have the weights of a trained model using CNN. This file can be used to load the model.
* Now, the loaded model can predict on the test dataset.
# Performance
The model achieves an accuracy of 94% on the test set.
# Credits
This project was created by Sourabh Kumawat.
