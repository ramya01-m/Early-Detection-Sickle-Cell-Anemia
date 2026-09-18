# Early Detection of Sickle Cell Anemia Using CNN

## 📌 Project Overview

**Early Detection of Sickle Cell Anemia** is a deep learning-based medical image classification project that aims to identify sickle cell anemia from microscopic blood smear images.

The project uses **Convolutional Neural Networks (CNN)** for extracting important image features and **MobileNet** as a lightweight feature extractor. The extracted features are then classified using **XGBoost** to distinguish between normal and sickle cell images.

## 🎯 Objectives

* Detect sickle cell anemia from blood smear images.
* Automate the image classification process using deep learning.
* Extract meaningful features from blood cell images using MobileNet.
* Classify the extracted features using XGBoost.
* Evaluate the model using standard classification metrics.

## 🛠️ Technologies Used

* **Python**
* **TensorFlow / Keras**
* **MobileNet**
* **XGBoost**
* **OpenCV**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Scikit-learn**

## 🧠 Methodology

The project follows these main steps:

1. **Dataset Collection**

   * Blood smear images are collected and organized into two classes:

     * Normal
     * Sickle

2. **Image Preprocessing**

   * Images are resized to **224 × 224** pixels.
   * Image data is prepared for deep learning processing.

3. **Feature Extraction**

   * **MobileNet** is used as a feature extractor.
   * Global Average Pooling is applied to obtain compact feature representations.

4. **Classification**

   * The extracted image features are provided to an **XGBoost classifier**.
   * The model predicts whether the image belongs to the Normal or Sickle class.

5. **Model Evaluation**

   * The performance is evaluated using:

     * Accuracy
     * Precision
     * Recall
     * F1-Score
     * Confusion Matrix

## 📂 Dataset Structure

```text
sickle-cell-disease-dataset/
│
├── Normal/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
│
└── Sickle/
    ├── image1.jpg
    ├── image2.jpg
    └── ...
```

## 📁 Project Structure

```text
Early-Detection-of-Sickle-Cell-Anemia/
│
├── code/
│   ├── SCA_code
│   
├── dataset/
│   └── README.md
│
├── output/
│   ├── Result.png
│
├── requirements.txt
│
└── README.md
```

## 📊 Results

The trained model is evaluated using classification metrics and visualizations such as the confusion matrix and performance graphs.

The final results and output screenshot is included in the **output** folder.

## 💡 Applications

This project can serve as a **computer-aided screening approach** for sickle cell image classification and can help demonstrate how deep learning can be applied to medical image analysis.

> **Note:** This project is intended for academic and research purposes and is not a substitute for professional medical diagnosis.

## 👩‍💻 Author

**M. Ramya**

B.Tech Information Technology

CSI College of Engineering
