#  Road Sign Classification using CNN

This project implements a **Convolutional Neural Network (CNN)** to classify traffic signs from the [GTSRB (German Traffic Sign Recognition Benchmark)](https://www.kaggle.com/datasets/valentynsichkar/traffic-signs-preprocessed) dataset.  

The model is trained on over 34,000 images of road signs and can predict the correct traffic sign when a user uploads an image.

---

## 📂 Dataset
- Source: [Traffic Signs Preprocessed Dataset](https://www.kaggle.com/datasets/valentynsichkar/traffic-signs-preprocessed)  
- Classes: 43 different types of traffic signs  
- Preprocessed images of size **32x32x3**

---

## 🏗️ Project Workflow
1. **Data Loading** (Pickle files for train, validation, test sets)  
2. **Preprocessing** (Normalization, reshaping)  
3. **CNN Model Building** using TensorFlow/Keras  
4. **Training & Validation** on dataset  
5. **Prediction** – upload any image and the model predicts the traffic sign  

---

## 📊 Model Performance
- Training data: **34,799 images**
- Validation data: **4,410 images**
- Test data: **12,630 images**
- Accuracy: ~**95%+** (depending on tuning)

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/road-sign-classification.git
   cd road-sign-classification
