# Machine Learning master course project
This repository contains student project that has been created for the purpose of Machine Learning course on the master studies at the Faculty of Mathematics, University of Belgrade.

## Team members
- Jovan Marković
- Petar Tešič

## Facial expression recognition
The final goal of this project is to create a model that will be able to recognize certain number of emotions on different pictures of different faces.

## Datasets
- CK+ - contains adaptaded data up to 920 images from 920 original CK+ dataset. Data is already reshaped to 48x48 pixels, in grayscale format and facecropped using haarcascade_frontalface_default. Emotions that are supported in this dataset are: angry, contempt, disgust, fear, happy, sadness, surprise.

- FER2013 - this dataset consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centred and occupies about the same amount of space in each image. The training set consists of 28,709 examples and the public test set consists of 3,589 examples. Emotions that are supported in this dataset are: angry, disgust, fear, happy, neutral, sad, surprise. 

## The structure of the repository
Repository contains the following items. Every single one of them is listed and briefly explained below:

- datasets.zip - extract this zip file into your current directory in order to get necessary datasets;

- preprocessing_functions.ipynb - contains necessary functions we used to process datasets we are working with; 

- 01_LBP_CK+_dataset.ipynb - this is a notebook in which we tested different models on CK+ dataset. We have created CNN, SVC and NN models. For SVC and NN we are using LBP preprocessing method;

- 02_Ensemble_FER2013_dataset.ipynb - this is a notebook in which we tested different models on FER2013 dataset. We have created CNN, SVC and NN models. For SVC and NN we are using LBP preprocessing method,
				      also, we are making more models using ensemble technique;

- 03_Processing_CK+_dataset.ipynb - notebook that tests different CNN models architectures on CK+ datasetl;

- 04_Processing_FER2013_dataset.ipynb - notebook that tests different CNN models architectures on FER2013 dataset.


## Conclusions
While CNN and NN models give best results on training set, the biggest disadvantage using neural networks is overfitting on train set. Using different kinds of regularizations we can manage those disadvantage, but it needs to be investigated futhermore. Using Local Binary Pattern technique in preprocessing, we're getting good results, but when we're working with models, we have two points in our code where we should look for optimization in order to get better performance, which can be tricky. Our models don't get satisfiable enough results, but this work is based on presenting different approaches in solving facial expression classification problems. 
