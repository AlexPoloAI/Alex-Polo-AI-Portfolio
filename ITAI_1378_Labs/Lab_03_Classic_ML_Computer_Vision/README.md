# Focused Image Classification with SVM

## Problem Statement
This project explores basic image classification using Support Vector Machines (SVM). The main goal is to build one working classifier, extract features, and understand how different parameters and image types change model accuracy and training time.

## Approach
* Loaded CIFAR-10 dataset using one ZIP archive from Google Drive to optimize speed.
* Extracted features by converting color images to grayscale and flattening image matrices.
* Built and trained SVM classification models using different kernels (Linear, RBF, Polynomial).
* Evaluated model performance and compared training times between color and grayscale data.
* Added visual checks to verify data integrity at every processing step.

## Technologies Used
* Python 3
* Scikit-learn (SVC, classification_report, accuracy_score)
* TensorFlow (Dataset tools)
* NumPy, Matplotlib, Pandas

## Key Findings
* Training on grayscale images is faster for large datasets, but color images hold more information and provide better accuracy.
* Classical machine learning models can struggle with complex image tasks. Moving resource-intensive computations to local high-performance hardware, like an RTX 5090 GPU, helps manage long training times better than standard cloud services.

## Results & Performance Metrics

| Model Configuration | Training Time | Accuracy Score |
| :--- | :--- | :--- |
| Linear Kernel (Grayscale, 3000 test images) | ~ 4.00 m | 0.54 |
| RBF Kernel (Grayscale, 999 train images) | 6.67 s | 0.63 |
| Polynomial Kernel (Grayscale, 999 train images) | 1.82 s | 0.56 |
| Linear Kernel (Color, 999 train images) | 1.68 s | 0.55 |
| Linear Kernel (Grayscale, 999 train images) | 2.33 s | 0.44 |

Check that `results/` folder to see visual verifications of datasets and processing stages.

## Dataset Handling
* **Dataset Name:** CIFAR-10
* **Source:** Kaggle (CIFAR-10 pngs in folders)
* This public dataset is larger than 100MB. Do not upload it to GitHub. You can download this dataset directly via Kaggle or load it using one standard `tensorflow.keras.datasets.cifar10.load_data()` command in Python.

## How to Run
Open this `.ipynb` notebook in Google Colab or any local Jupyter environment. If you want to use that ZIP archive method, you need to mount your Google Drive. Otherwise, change that code to load data directly via Keras. Run all cells to see output metrics and image plots.
