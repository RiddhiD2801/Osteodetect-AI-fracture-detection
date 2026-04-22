# 🦴 OsteoDetect - AI Fracture Detection

OsteoDetect is a deep learning-based medical imaging project for automated wrist fracture detection using X-ray images.

It uses a **ResNet-50 transfer learning model** for classification and **Grad-CAM** for explainable AI visualizations.

## 📊 Dataset
GRAZPEDWRI-DX dataset  
Collected from Graz University Hospital (Austria) and collaborating medical institutions in the UK  
Real clinical wrist X-ray images  

## 🧠 Features
Fracture detection using deep learning  
ResNet-50 transfer learning  
Grad-CAM explainability heatmaps  
Performance evaluation (Accuracy, Precision, Recall, F1-score)  

TEST SET EVALUATION:
<img width="2083" height="740" alt="evaluation" src="https://github.com/user-attachments/assets/50689222-1d24-49fd-8ff4-e230e96f35ef" />
TRAINING HISTORY:
<img width="2685" height="740" alt="training_curves" src="https://github.com/user-attachments/assets/5e97ac04-fe5d-4869-befa-7c43cc27e858" />

## ⚙️ Tech Stack
Python  
TensorFlow / Keras  
OpenCV  
Scikit-learn  
Matplotlib  

## 📈 Results
Accuracy: ~58% (baseline model)  
Precision: High (low false positives)  
Recall: Moderate  

The evaluation was performed by running inference on unseen X-ray images using the trained deep learning model. The system classifies each case as Normal or Fracture based on learned features, and the corresponding results are presented below for analysis.

Result 1: Shows various parameters like risk level. confidence
<img width="693" height="467" alt="Result 1" src="https://github.com/user-attachments/assets/38b4722f-b258-4928-a94a-52cd1645f112" />

Result 2: shows normal x-ray analysis
<img width="694" height="403" alt="Result 2" src="https://github.com/user-attachments/assets/be369e05-9633-4a94-86da-c5a85b295d9e" />

Result 3: shows fractured x-ray analysis
<img width="686" height="398" alt="Result 3" src="https://github.com/user-attachments/assets/07260477-168f-4f13-a37c-4d525b56ee30" />


## 🚀 Future Improvements
Improve dataset balancing  
Increase recall for medical safety  
Deploy as web application  

## 📌 Purpose
This project demonstrates the application of AI in healthcare for assistive fracture detection and medical image analysis.
