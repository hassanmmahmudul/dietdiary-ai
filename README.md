# DietDiary AI
## Image processing, Android Application

An AI-powered Android application that helps users track their meals by analyzing food images and estimating nutritional values using deep learning and third-party APIs.

## 🧠 Overview

**DietDiaryAI** is a mobile application designed to make meal tracking effortless. Users simply take or upload photos of their meals, and the app automatically estimates the food type, portion size, and nutritional content. This is achieved through computer vision and convolutional neural networks (CNNs). The goal is to promote healthier eating habits, especially for fitness-conscious individuals, students, and first-time diet trackers.

---

**Key Contributions**

* ✅ Designed and trained deep learning models (CNNs) such as **MobileNet** and **ResNet** for image-based food recognition and portion estimation
* ✅ Developed an **Android mobile application** enabling users to log meals via food image capture for automated nutrition tracking
* ✅ Integrated **TensorFlow Foodvisor API Vision** to enrich food image data with real-time nutritional information
* ✅ Created **UI/UX designs using Figma**, including wireframes for dashboard, meal logging, user profiles, and nutrition insights

---
## 🔧 Technical Stack

### 📱 Mobile App

* **Platform**: Android (Java/Kotlin)
* **Features**:

  * Capture or upload food images
  * View dashboard of daily calorie/macronutrient stats
  * Personalized profile with nutrition goals
  * Meal journal and history

### 🤖 Machine Learning

* **Models**:

  * **Convolutional Neural Networks (CNNs)**: Trained MobileNet and ResNet variants for food classification and portion size estimation
  * **Image preprocessing**: Resizing, normalization, and data augmentation techniques

* **Frameworks**:

  * TensorFlow, Keras

* **Dataset**:

  * Public food image datasets (e.g., Food-101); preprocessed for training food classification models

### 🔌 API Integration

* **TensorFlow Foodvisor Vision API**

  * Used for real-time estimation of calorie content and macronutrients
  * Parses food image to extract nutrition data and enrich app insights

### 🎨 UI/UX Design

* **Tool**: Figma
* **Design Components**:

  * Dashboard for caloric intake overview
  * Meal logging via camera or gallery
  * Profile settings with macro goals
  * Journal for tracking progress over time

---

## 🚀 Key Features

* AI-based food recognition from images
* Real-time nutrition analysis (calories, proteins, carbs, fats)
* User-friendly dashboard and meal logging
* Modular architecture for future expansion (e.g., video consultations with nutritionists)

---

## 📊 Future Enhancements

* Personalized suggestions based on eating habits
* Integration with wearables for holistic health tracking
* Enhanced accuracy via custom-trained datasets
