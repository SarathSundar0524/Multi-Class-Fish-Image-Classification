# 🐟 Multiclass Fish Image Classification

## 📌 Project Overview
This project focuses on classifying fish images into multiple categories using Deep Learning. It includes building a CNN model from scratch and applying Transfer Learning using pre-trained models to improve performance.

The project also includes model evaluation, comparison, and deployment using a Streamlit web application for real-time predictions.

---

## 🎯 Domain
Image Classification

---

## 🧠 Skills Gained
- Deep Learning  
- Python  
- TensorFlow / Keras  
- Data Preprocessing  
- Transfer Learning  
- Model Evaluation  
- Data Visualization  
- Streamlit Deployment  

---

## ❗ Problem Statement
The objective is to classify fish images into multiple species using deep learning models by:
- Training a CNN from scratch  
- Using pre-trained models (Transfer Learning)  
- Comparing model performance  
- Deploying the best model  

---

## 💼 Business Use Cases
- **Enhanced Accuracy:** Identify the best-performing model  
- **Model Comparison:** Evaluate multiple architectures  
- **Deployment Ready:** Real-time prediction using web app  

---

## 🛠️ Approach

### 1️⃣ Data Preprocessing & Augmentation
- Rescale images to [0,1]  
- Apply:
  - Rotation  
  - Zoom  
  - Horizontal flip  

---

### 2️⃣ Model Training

#### 🔹 CNN (Custom Model)
- Built from scratch  
- Used as baseline  

#### 🔹 Transfer Learning Models
- VGG16  
- ResNet50  
- MobileNet  
- InceptionV3  
- EfficientNetB0  

- Pre-trained on ImageNet  
- Fine-tuned on dataset  

---

### 3️⃣ Model Evaluation
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

---

### 4️⃣ Model Selection
- Compared all models  
- Selected best model based on accuracy  
- Saved model in `.h5 / .pkl` format  

---

### 5️⃣ Deployment (Streamlit App)
Features:
- Upload fish image  
- Predict category  
- Show confidence score  

---

## 📂 Dataset
- Fish image dataset organized by folders  
- Loaded using ImageDataGenerator  
- Provided as ZIP file  

---

## 📦 Project Deliverables
- Trained Models (.h5 / .pkl)  
- Streamlit Application  
- Python Scripts  
- Model Comparison Report  
- GitHub Repository  

---

## ▶️ How to Run

💡 Make sure Python 3.8+ is installed  

### 1. Clone the repository
```bash
git clone https://github.com/your-username/fish-classification.git
cd fish-classification
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Train the model (optional)
```bash
python train.py
```

### 4. Run Streamlit app
```bash
streamlit run app.py
```

---

## 📊 Output
- Accuracy & loss graphs  
- Confusion matrix  
- Model comparison  
- Real-time predictions  

---

## 🔮 Future Improvements
- Hyperparameter tuning  
- Larger dataset  
- Cloud deployment  
- Real-time camera prediction  

---

## 👨‍💻 Author
Sarath Sundar  
Mechatronics Engineer | Data & AI Enthusiast  
