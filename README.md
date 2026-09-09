# 🩺 Medical Image Classification
---
## **📖Problem Statement**
Chest X-ray analysis is widely used to detect lung diseases, but manual interpretation is:
* Time-consuming
* Requires expert radiologists
---
## **🎯Objective**
The system should :
* Analyze chest X-ray images automatically
* Detect lung disease patterns
* Classify images into: COVID / PNEUMONIA / NORMAL
* Assist medical professionals in faster screening
---
## **ℹ️Approach**
| Traditional method | CNN based method |
|--------------------|------------------|
| Handcrafted filters & rules | Learns patterns from data |
| Limited to known patterns | Extracts spatial features |
| Cannot generalize well | Generalizes to new images |
---
## **🔄Project Workflow**
### **Pipeline:**
* Problem Statement & Data Exploration
* Data Loading & Preprocessing
* Model Architecture & Training Setup
* Model Training & Validation
* Model Performance Testing
### **Workflow**
'Load → Preprocess → Train → Valid'
---
## **🧠Classification Goal**
This project classifies chest X-ray images into: 
* COVID-19
* NORMAL
* PNEUMONIA
### **Input:** 
224 × 224 Grayscale Image
### **Output**
3-Class Prediction
### **Prototype**
