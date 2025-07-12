# Facial Expression Recognition  
**Machine Learning Master Course Project**  
*Faculty of Mathematics, University of Belgrade*

---

## 👥 Team Members
- **Jovan Marković**
- **Petar Tešić**

---

## 🎯 Project Overview

The goal of this project is to build machine learning models capable of recognizing facial expressions (emotions) from grayscale images. This includes exploring various classification algorithms and preprocessing techniques, and experimenting on two popular datasets: **CK+** and **FER2013**.

---

## 🗂 Datasets

### 📁 CK+ Dataset
- Contains ~920 grayscale, 48×48 pixel face-cropped images.
- Preprocessed using Haar cascade (`haarcascade_frontalface_default`) for face detection.
- **Supported emotions**: Angry, Contempt, Disgust, Fear, Happy, Sadness, Surprise.

### 📁 FER2013 Dataset
- Contains 28,709 training and 3,589 public test images (48×48 pixels, grayscale).
- Faces are centered and standardized.
- **Supported emotions**: Angry, Disgust, Fear, Happy, Neutral, Sad, Surprise.

---

## 🧪 Repository Structure

| File/Folder | Description |
|-------------|-------------|
| `datasets.zip` | Compressed folder with CK+ and FER2013 datasets (extract before running notebooks). |
| `preprocessing_functions.ipynb` | Helper functions for preprocessing, including face detection and LBP. |
| `01_LBP_CK+_dataset.ipynb` | SVC, NN, and CNN model experiments on CK+ dataset using LBP preprocessing. |
| `02_Ensemble_FER2013_dataset.ipynb` | Experiments on FER2013 using SVC, NN, CNN, and ensemble techniques. |
| `03_Processing_CK+_dataset.ipynb` | CNN architecture experiments on the CK+ dataset. |
| `04_Processing_FER2013_dataset.ipynb` | CNN architecture experiments on the FER2013 dataset. |

---

## 📊 Key Findings & Conclusions

- **CNN and NN models** perform well on training sets, but suffer from **overfitting**.
- Regularization techniques help, but require further tuning.
- **Local Binary Pattern (LBP)** preprocessing yields good feature extraction for simpler models like SVC and NN.
- Despite not achieving top-tier results, the project demonstrates a variety of approaches to solving the **facial emotion classification** problem.
- Further optimization is needed in both **data preprocessing** and **model fine-tuning** to improve generalization on test data.

---
