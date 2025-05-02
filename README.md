# 😊 Face Emotion Detection

A real-time facial emotion detection system using **CNN** and **OpenCV**, capable of recognizing 7 human emotions through webcam input.

## 🔍 Features

- Real-time webcam-based emotion detection
- Classifies: Happy, Sad, Angry, Neutral, Fear, Surprise, Disgust
- Uses Haar cascades for face detection
- CNN model (Keras) for emotion recognition

## 🛠 Tech Stack

**Python**, **TensorFlow/Keras**, **OpenCV**, **NumPy**, **Jupyter Notebook**

## 📁 Key Files

- `main.ipynb` – Run emotion detection via webcam
- `emotion_model.h5/json` – Pretrained CNN model
- `haarcascades/` – Face detection XML files
- `Emotion_detection_with_CNN-main/` – Training scripts and utilities

## 🚀 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/Boahan/Face-Emotion-Detection.git
   cd Face-Emotion-Detection
````

2. Install dependencies:

   ```bash
   pip install -r Emotion_detection_with_CNN-main/requirements.txt
   ```
3. Run in Jupyter:

   ```bash
   jupyter notebook
   ```

   Open and run `main.ipynb`.

## 📌 Notes

* Ensure your webcam is connected and accessible
* Tested on Python 3.8+ and TensorFlow 2.x


