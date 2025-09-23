# 🧠 Brain Tumor Detection using Convolutional Neural Networks (CNN)

## 📌 Project Overview

This project applies **deep learning techniques** to detect and classify brain tumors from MRI scans.
A **Convolutional Neural Network (CNN)** model was designed and trained to categorize MRI images into four classes:

* **Glioma**
* **Meningioma**
* **Pituitary**
* **No Tumor**

## ⚡ Features

* Image preprocessing and cleaning for consistency
* Data augmentation techniques to improve generalization
* CNN architecture built with **TensorFlow/Keras**
* Training and validation with performance visualization
* Achieved **96% accuracy** on test dataset

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:** TensorFlow, Keras, NumPy, Pandas, Matplotlib, Seaborn, OpenCV

## 📂 Project Structure

```
brain_tumor_detection.ipynb   # Jupyter Notebook containing the CNN pipeline
dataset/                      # Brain MRI dataset (not included, add your own)
```

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/princek9109/Brain-Tumor-Detection-CNN.git
   cd Brain-Tumor-Detection-CNN
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Add the dataset to the `dataset/` folder.

   * Dataset used: **Brain MRI Images** (Glioma, Meningioma, Pituitary, No Tumor)
   * You can download publicly available datasets from Kaggle.
4. Open the notebook:

   ```bash
   jupyter notebook brain_tumor_detection.ipynb
   ```

## 📊 Results

* CNN achieved **96% test accuracy**
* Effective visualization of predictions and training progress
* Robust model with augmentation techniques reducing overfitting

## 🤝 Contribution

Contributions and improvements are welcome! Fork the repo and create a pull request.

## 📜 License

This project is released under the **MIT License**.
