# Facial Emotion Detection Based On Convolutional Neural Network
Used Convolutional neural networks (CNN) for facial expression recognition . The goal is to classify each facial image into one of the three main facial emotion categories (Happiness, Sadness, Neutral) considered.

The project explanation is available on [my Youtube channel](https://youtu.be/FYRRrsnt8ng)

# Data 
The model is trained and tested on the dataset from [Kaggle](https://www.kaggle.com/deadskull7/fer2013), which comprises 48-by-48-pixel grayscale images of human faces,each labeled with one of 7 emotion categories: anger, disgust, fear, happiness, sadness, surprise, and neutral . 

Image set of 35,887 examples, with training-set : dev-set: test-set as 80 : 10 : 10 .

# Usage:

This project is in notebook format. It was written using jupyter notebook.

# Library Used
* Keras
* Sklearn
* Numpy
* Tensorflow
* Tkinter

# Getting started

1. Download the csv file from [FER2013 dataset](https://www.kaggle.com/deadskull7/fer2013)
2. No need to train the model , already trained weights saved in ```model.h5 file```
3. If you want to re-train the model or update it you'll find it in the ```learn_emotion.ipynb``` file.
4. To load and test individual image you will find a GUI in ```GUI.ipynb``` file.

# Model Evaluation
Accuracy Achieved 78.54%
