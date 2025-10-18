# 🧠 Skin Disease Detection Using Deep Learning  

## 📋 Overview  
Skin diseases are a major global health concern, impacting millions of individuals across all age groups. Accurate and timely diagnosis is crucial for effective treatment and management. Traditionally, diagnosis relies on visual inspection by dermatologists — a process that can be **subjective, time-consuming**, and prone to human error.  

In this project, we propose a **deep learning-based approach** for automated skin disease detection. Leveraging state-of-the-art convolutional neural networks (CNNs), our model learns intricate visual patterns directly from skin images, enabling **accurate and efficient disease classification**.  

---

## 🎯 Objective  
To develop a deep learning model capable of classifying multiple types of skin diseases using image data, and to identify the most effective architecture among leading CNN models.

---

## 🧩 Methodology  

### 1. **Dataset**  
- Total Images: **5,000**  
- Categories: **Acne**, **Eczema**, **Psoriasis**, **Ringworm**  
- Dataset split into **training**, **validation**, and **test** sets.  

### 2. **Data Preprocessing & Augmentation**  
- Image resizing and normalization.  
- Data augmentation (rotation, flipping, zooming) to improve generalization.  
- Noise reduction and contrast enhancement for improved clarity.  

### 3. **Model Architectures Evaluated**  
- **ResNet50**  
- **VGG16**  
- **Inception V3**  
- **EfficientNet**  

Each model was trained for **10 epochs** using transfer learning techniques.  

---

## ⚙️ Experimental Results  

| Model        | Validation Accuracy | Test Accuracy | Precision | Recall | F1-Score |
|---------------|---------------------|----------------|------------|----------|-----------|
| **EfficientNet** | **66.7%** | **74.48%** | **89%** | **72%** | **79%** |
| ResNet50      | 41.14%             | -              | -          | -        | -         |
| VGG16         | 39.52%             | -              | -          | -        | -         |
| Inception V3  | 38.27%             | -              | -          | -        | -         |

---

## 🔍 Confusion Matrix Insights  
The model performed well across all four classes, with the following **True Positive Rates**:  
- **Acne:** 88.7%  
- **Eczema:** 75.4%  
- **Psoriasis:** 64.73%  
- **Ringworm:** 79.33%  

---

## 🏆 Key Findings  
- **EfficientNet** outperformed all other architectures, achieving the highest accuracy and generalization.  
- Data augmentation significantly improved model performance and robustness.  
- The approach demonstrates strong potential for **AI-assisted dermatological diagnostics**.  

---

## 🚀 Future Work  
- Expand the dataset with more diverse skin tones and conditions.  
- Implement explainable AI (XAI) methods to improve interpretability for clinicians.  
- Explore lightweight model deployment for mobile or telemedicine platforms.  

---

## 📚 References  
- He, K. et al. *“Deep Residual Learning for Image Recognition.”* CVPR, 2016.  
- Tan, M. & Le, Q.V. *“EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks.”* ICML, 2019.  
