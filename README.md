# Active-or-Absent-AI-Based-Fatigue-Detection-for-E-Learning-Environments
# 🎓 Active or Absent? AI-Based Fatigue Detection for E-Learning Environments

A computer vision and machine learning project that monitors student alertness during online classes using webcam-based facial and postural analysis. Built using MediaPipe, OpenCV, and Logistic Regression, the system classifies whether a student is "Active" or "Tired" in real time, helping institutions better understand engagement in virtual learning environments.

---

## 📌 Features

- 🔍 **Real-time image capture** using webcam
- 🧠 **Facial and posture landmark detection** with MediaPipe
- 📐 **Feature engineering** using EAR (Eye Aspect Ratio), MAR (Mouth Aspect Ratio), and slouch angle
- 🤖 **Fatigue classification model** using Logistic Regression
- 📊 **Model training, testing, and evaluation**
- 🖼️ **Overlay detection result** directly on webcam frames
- 💾 Model persistence using `joblib` for future reuse

---

## 🚀 Use Case

In the age of online learning, monitoring student engagement has become a challenge. This system aims to assist:
- Teachers tracking students’ alertness during lectures
- E-learning platforms integrating fatigue-aware systems
- Researchers analyzing human behavior during screen time

---

## 🛠️ Tech Stack

| Tool | Description |
|------|-------------|
| Python | Core programming language |
| OpenCV | Image processing and webcam integration |
| MediaPipe | Facial and pose landmark detection |
| scikit-learn | ML model training & evaluation |
| Pandas | Data handling and analysis |
| Google Colab | Development environment |

---

## 🧮 Key Features Extracted

- **EAR (Eye Aspect Ratio)** for both eyes
- **MAR (Mouth Aspect Ratio)**
- **Slouch Angle** from shoulder and hip landmarks

These features are used as inputs to the fatigue classification model.

---

## 📈 Model Performance

- **Model Used**: Logistic Regression  
- **Evaluation Metric**: Classification Report  
- **Classes**: 
  - `Active (0)`
  - `Tired (1)`  
- **Accuracy Achieved**: *~85% (based on small sample set)*

---

## 🖥️ Demo

![MindMood Demo](demo.gif) <!-- Optional: Add your project demo gif or screenshot here -->

---

## 📂 File Structure

