# Machine Learning master course project
This repository contains student project that has been created for the purpose of Machine Learning course on the master studies of the Faculty of Mathematics, University of Belgrade.

## Facial expression recognition
The final goal of this project is to create a model that will be able to recognize certain number of emotions on different pictures of different faces.

## Datasets
- CK+ - contains adaptaded data up to 920 images from 920 original CK+ dataset. Data is already reshaped to 48x48 pixels, in grayscale format and facecropped using haarcascade_frontalface_default. Emotions that are supported in this dataset are: angry, contempt, disgust, fear, happy, sadness, surprise.
- FER2013 - this dataset consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centred and occupies about the same amount of space in each image. The training set consists of 28,709 examples and the public test set consists of 3,589 examples. Emotions that are supported in this dataset are: angry, disgust, fear, happy, neutral, sad, surprise. 

## The structure of the repository
Repository consists of three the most important jupyter notebooks (there are some others notebooks, but there are not that relevant). Those are:
- 00_Preprocessing_Functions.ipynb
- 01_Processing_FER2013_dataset.ipynb
- 02_Processing_CK+_dataset.ipynb

## Team members
- Jovan Marković
- Petar Tešič

