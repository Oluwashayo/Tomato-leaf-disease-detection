# 🍅 Tomato Leaf Disease Detection Using Deep Neural Network  

## 📌 Overview  
This project presents a **deep learning-based solution** for detecting tomato leaf diseases using **MobileNetV2** and **transfer learning**. The model was trained on the **PlantVillage dataset** with 10 classes (9 diseases + 1 healthy) and optimized for **mobile deployment** using **TensorFlow Lite**.  


This work aims to empower farmers, especially in **Nigeria and other developing regions**, with an accessible, offline-capable diagnostic tool to improve crop management and food security.  

---

## ⚙️ Methodology  
1. **Dataset**: PlantVillage tomato leaf subset (~18,000 images).  
2. **Preprocessing**: Image resizing (224×224), normalization, and augmentation.  
3. **Model Architecture**: MobileNetV2 + Transfer Learning + Dropout + Softmax classifier.  
4. **Training**: Adam optimizer, categorical cross-entropy loss, 20 epochs in total.  
5. **Deployment**: Converted and quantized with **TensorFlow Lite** for mobile use.  

---

## 📊 Results  
- **Validation Accuracy**: 92%  
- **Deployment**: Lightweight TFLite model suitable for low-resource smartphones.  

---

## 🚀 Features  
- Real-time tomato disease detection via mobile app.  
- Works offline (no internet required).  
- Optimized for **farmers in remote or resource-limited regions**.  

