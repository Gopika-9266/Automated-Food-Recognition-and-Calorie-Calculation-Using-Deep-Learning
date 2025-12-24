# 🍽️ Automated Food Recognition and Calorie Calculation using Deep Learning

## 📌 Overview
This project implements a deep learning–based system to automatically recognize food items from images and estimate their calorie values. It reduces manual calorie tracking and improves dietary monitoring accuracy.

---

## 🎯 Objectives
- Detect food items from images
- Estimate calorie values using a nutrition database
- Automate dietary tracking

---

## 🧠 Technologies Used
- Python  
- CNN (YOLO / EfficientNet)  
- TensorFlow / PyTorch  
- OpenCV  

---

## 🔄 Methodology
1. Collect food images from Food-101 and UECFood-256 datasets  
2. Preprocess images (resizing and normalization)  
3. Train CNN-based models for food detection  
4. Map detected food items to calorie values  
5. Display estimated calories  

---

## 📊 Results
- Accuracy: **90–93%**
- EfficientNet shows better performance
- Works well for clear food images

---

## 🖼️ Output Screens

### 🔐 Login Page
<img width="531" height="336" alt="image" src="https://github.com/user-attachments/assets/2985bc10-ec5c-4459-8133-d654bd039d69" />

### 📤 Image Upload
<img width="610" height="166" alt="image" src="https://github.com/user-attachments/assets/4f7d05a5-f28f-4d45-b53d-e9a4b0049d30" />


### 🍱 Food Detection & Calorie Output
<img width="584" height="442" alt="image" src="https://github.com/user-attachments/assets/10a3fa9d-14a3-4ce0-b9f2-cb060d2fc54f" />
<img width="521" height="354" alt="image" src="https://github.com/user-attachments/assets/153fe2e2-f0b8-4f38-8aa2-19e467c72e82" />


---

## ✅ Conclusion
The system successfully automates food recognition and calorie estimation, making dietary tracking efficient and user-friendly.

---

## 🔮 Future Enhancements
- Improved portion-size estimation
- Support for mixed dishes
- Mobile app deployment

---

## 📦 Requirements
```txt
python>=3.8
tensorflow
torch
opencv-python
numpy
matplotlib
