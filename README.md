# Multi-Class-Fish-Image-Classification
## Project Overview
--------- 
This project focuses on classifying fish images into multiple categories using Deep Learning techniques. It involves building a custom CNN model and leveraging Transfer Learning with pre-trained architectures to improve classification performance.
The project also includes model evaluation, comparison, and deployment through a Streamlit web application for real-time predictions.

### Domain
Skills Gained
Deep Learning
Python
TensorFlow / Keras
Data Preprocessing
Transfer Learning
Model Evaluation
Data Visualization
Streamlit Deployment
### Problem Statement

The objective is to classify fish images into multiple species categories using deep learning models. The task includes:

Training a CNN model from scratch
Applying transfer learning using pre-trained models
Comparing performance across models
Deploying the best model for real-time predictions

### Business Use Cases
Enhanced Accuracy: Identify the most effective model for fish classification
Model Comparison: Analyze performance across multiple architectures
Deployment Ready: Provide a user-friendly web app for real-time predictions
### Approach
### Data Preprocessing & Augmentation
Rescale pixel values to [0,1]
Apply augmentation techniques:
Rotation
Zoom
Horizontal flipping
### Model Training
🔹 Custom CNN
Built from scratch
Used as baseline model
🔹 Transfer Learning Models
VGG16
ResNet50
MobileNet
InceptionV3
EfficientNetB0
Pre-trained on ImageNet
Fine-tuned on fish dataset
### Model Evaluation
Metrics used:
Accuracy
Precision
Recall
F1-score
Confusion matrix analysis
Training vs validation accuracy/loss visualization
### Model Selection
Compared all models
Selected the best-performing model based on accuracy

Saved model in:

.h5 / .pkl format
5️⃣ Deployment (Streamlit App)

Features:
Upload fish image
Predict fish category
Display prediction confidence


## Output
Model performance comparison
Accuracy & loss graphs
Confusion matrix
Real-time predictions via Streamlit


 # Author

Sarath Sundar
Mechatronics Engineer | Data & AI Enthusiast

