# AgriAid

**AI-Powered Crop Disease Detection and Assistance System**

---

## 📌 Project Overview

**AgriAid** is an Android-based mobile application designed to assist farmers in identifying crop leaf diseases using Artificial Intelligence. By leveraging deep learning–based image classification, the application enables users to capture or upload images of crop leaves and receive instant disease identification along with basic remedial guidance.

The system is optimized for real-world agricultural conditions and aims to bridge the gap between advanced AI technology and practical farming needs.

---

## 🎯 Objectives

* To automate crop disease detection using image-based deep learning models
* To provide farmers with fast and reliable disease identification
* To minimize crop loss through early diagnosis
* To design a simple and farmer-friendly mobile interface
* To deploy a lightweight AI model suitable for low-end Android devices

---

## 🧠 System Architecture

The AgriAid system follows a modular architecture:

1. **User Interface (Android App)**

   * Camera capture and gallery image upload
   * Simple result display with confidence score

2. **AI Model Layer**

   * Convolutional Neural Network (CNN)
   * Optimized using TensorFlow Lite (TFLite)

3. **Processing Layer**

   * Image preprocessing (resize, normalization)
   * Model inference on-device

4. **Output Layer**

   * Disease name
   * Confidence score
   * Suggested remedial action

---

## 🛠️ Technologies Used

### Software & Frameworks

* **Android Studio**
* **Java / Kotlin**
* **TensorFlow & TensorFlow Lite**
* **Python (Model Training)**

### Machine Learning

* Convolutional Neural Networks (CNN)
* Data Augmentation Techniques
* Transfer Learning (MobileNet-style architecture)

### Tools

* Google Colab & Jupyter Notebook (Model training)
* OpenCV (Image preprocessing)

---

## 📂 Project Structure

```
AgriAid/
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   ├── res/
│   │   │   └── AndroidManifest.xml
│
├── model/
│   ├── trained_model.tflite
│
├── dataset/
│   ├── healthy/
│   ├── diseased/
│
├── README.md
---

## 📱 Application Features

* Capture crop leaf images using mobile camera
* Upload images from device gallery
* Real-time disease prediction
* Confidence score display
* Lightweight and fast inference
* Offline model execution after installation

---

## ⚙️ Installation & Setup

### Prerequisites

* Android Studio (latest stable version)
* Android device (Android 8.0+)
* Internet connection (initial setup only)

### Steps

1. Open the project in Android Studio
2. Sync Gradle dependencies
3. Connect an Android device or emulator
4. Build and run the application

---

## 📊 Dataset Description

* Leaf images collected from public agricultural datasets
* Multiple crop categories and disease classes
* Data augmentation applied:

  * Rotation
  * Zoom
  * Brightness adjustment
  * Horizontal flipping

These techniques improve robustness under real farm lighting conditions.

---

## 🧪 Model Training & Optimization

* CNN trained using supervised learning
* Validation used to monitor overfitting
* Model optimized for mobile deployment
* Converted to TensorFlow Lite format
* Accuracy trade-offs balanced against inference speed

---

## 📈 Results

* High accuracy on common crop diseases
* Acceptable performance on low-end devices
* Slight accuracy reduction after TFLite conversion, within acceptable limits
* Fast real-time predictions

---

## 🚧 Limitations

* Limited to diseases present in the training dataset
* Accuracy depends on image quality
* Does not replace expert agricultural consultation

---

## 🔮 Future Enhancements

* Support for more crops and diseases
* Multilingual support for farmers
* Cloud-based expert recommendations
* Integration with weather and soil data
* Voice-based interaction

---

## 👨‍🎓 Academic Relevance

This project demonstrates practical application of:

* Machine Learning
* Deep Learning
* Mobile Application Development
* AI model optimization
* Real-world problem solving in agriculture

It is suitable for **final-year engineering project submission**.

---

## 📜 License

This project is developed for academic purposes.
Reuse or modification should credit the original authors.

---