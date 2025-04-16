# Breast Ultrasound Image Classification Using Deep Learning

## Overview

This project implements a deep learning model for the classification of breast ultrasound images into three categories: **benign**, **malignant**, and **normal**. Utilizing a pre-trained VGG19 convolutional neural network model, the system is designed to assist radiologists in the early detection and diagnosis of breast cancer with high accuracy and consistency.

The project was developed as part of the coursework at **Dayananda Sagar University**, Department of Computer Science and Engineering (AI & ML), and is based on a comprehensive methodology that includes data preprocessing, augmentation, model fine-tuning, and performance evaluation.

---

## Project Structure

- `Breast_Ultrasound_Classification.ipynb` – The complete Python Jupyter Notebook containing all code for dataset processing, model training, and evaluation.
- `Special Topic Report Final.pdf` – A detailed report explaining the background, methodology, results, and future work.

---

## Dataset

The dataset used in this project is the **Breast Ultrasound Images Dataset (BUSI)**, which contains labeled ultrasound images categorized as benign, malignant, or normal. It was obtained from a public repository and is freely available here:

🔗 [Breast Ultrasound Images Dataset – Kaggle](https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset)

---

## Highlights

- **Model Used:** Pre-trained VGG19 (fine-tuned for this task)
- **Frameworks:** TensorFlow and Keras
- **Image Preprocessing:** Resizing to 224x224, normalization, and data augmentation (scaling, rotation, flipping)
- **Classification Categories:** Benign, Malignant, Normal
- **Performance Evaluation:** Training and validation accuracy plots, sample predictions, and test evaluations

---

## Results

The model was trained for 20 epochs and achieved high accuracy in classifying breast ultrasound images across all three categories. The report includes accuracy plots and test case visualizations to support the findings.


