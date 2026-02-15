# 🩺 Diabetic Retinopathy Detection Using Deep Learning

## 📌 Project Overview
Diabetic Retinopathy (DR) is a diabetes complication that affects the eyes and can lead to blindness if not detected early.  

This project builds a Convolutional Neural Network (CNN) model to classify retinal fundus images and detect signs of diabetic retinopathy automatically.

The goal is to assist ophthalmologists in early diagnosis using AI-based screening.

---

## 📊 Dataset

- 200 Training Images
- 70 Testing Images
- Image Type: Retinal Fundus Images
- Binary Classification:
  - DR Positive
  - DR Negative

Images were preprocessed and resized before model training.

---

## 🛠 Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Scikit-learn

---

## 🧠 Model Architecture

The model uses a Convolutional Neural Network (CNN) with:

- Convolution Layers
- ReLU Activation
- MaxPooling Layers
- Flatten Layer
- Fully Connected Dense Layers
- Sigmoid Output Layer (Binary Classification)

---

## 🔍 Workflow

1. Data Collection
2. Data Preprocessing
   - Image resizing
   - Normalization
3. Model Building (CNN)
4. Model Training
5. Model Evaluation
6. Performance Visualization

---

## 📈 Results

- Training Accuracy
- Testing Accuracy
- Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - Confusion Matrix

---

## 🚀 Future Improvements

- Increase dataset size
- Use Transfer Learning (ResNet, EfficientNet)
- Deploy as a web app (Flask / FastAPI)
- Multi-class severity detection

---

## 📂 Project Structure
diabetic-retinopathy-detection-ml/
│
├── data/
│   ├── raw/
│   └── sample_images/
│
├── notebooks/
│
├── src/
│
├── models/
│
├── requirements.txt
|
└── README.md
