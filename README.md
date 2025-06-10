# Face Mask Detection App 😷📱

## 📱 Overview
A mobile app that detects face mask usage in real-time using a custom model trained with [Teachable Machine](https://teachablemachine.withgoogle.com/). The model classifies faces into three categories: **With Mask**, **Without Mask**, and **Incorrect Mask**.

## 🧠 Classes Detected
- 😷 **With Mask**  
- ❌ **Without Mask**  
- ⚠️ **Incorrect Mask Position**

## 🛠️ Tools Used
- Teachable Machine (Image Classification)
- TensorFlow Lite (Model Deployment)
- Android Studio (Mobile App)
- Java/Kotlin (Integration & Camera Handling)

## 🚀 How It Works
1. Collected and labeled images for three classes
2. Trained a model using Google's Teachable Machine
3. Exported the model as a `.tflite` file
4. Integrated it into an Android application
5. Used device camera to classify mask status in real-time

## 📸 Screenshots
## 📸 Screenshots

![Face Mask App Screenshot](./screen_app.jpg)

## 📁 Files
- `model.tflite` – Trained model (Not included here)
- `labels.txt` – Class labels: with_mask, without_mask, incorrect_mask
