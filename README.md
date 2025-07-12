# 🚦 Traffic Sign Recognition using CNN

This project uses the **German Traffic Sign Recognition Benchmark (GTSRB)** dataset to build a **Convolutional Neural Network (CNN)** that classifies images of traffic signs into 43 categories. It was developed and trained using **Google Colab** and **TensorFlow/Keras**.

---

## 📁 Dataset

- **Source**: [GTSRB Dataset](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)
- Contains 43 classes of traffic signs.
- Images are categorized in folders named `0` to `42`.
- Uploaded as a ZIP file to Google Drive and extracted in Colab.

---

## 🧰 Tech Stack

- 🐍 Python
- 🧠 TensorFlow / Keras
- 🧮 NumPy, Matplotlib, OpenCV
- 📊 Scikit-learn
- 📁 Google Colab

---

## 🚀 Features

- ✅ Image Preprocessing and Normalization
- ✅ CNN Model Architecture
- ✅ Training & Evaluation with Accuracy Plot
- ✅ Prediction on Sample Images
- ✅ Model Saving (`.h5`)
- ✅ Visual Output with `matplotlib`

---

## 🧪 Model Performance

- Achieved **~94–97% accuracy** on test data (varies per run)
- Validation and training loss converge smoothly
- Model generalizes well on unseen traffic sign images

---

## 📷 Sample Prediction

> **Actual Label**: 1 (30 speed limit
> **Predicted Label**: 1 ✅  
---

## 💾 How to Use

1. Upload `GTSRB.zip` to your Google Drive
2. Mount drive in Google Colab
3. Extract ZIP and preprocess images
4. Train the CNN using provided code
5. Predict test images
6. Save the model (`.h5` format)
