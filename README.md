# Human Emotion Detection from Voice

This project is a machine learning-based system that detects human emotions from voice recordings using audio feature extraction and classification techniques. The system is trained on the RAVDESS dataset and deployed via a Streamlit web app.

---

## 📌 Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

---

## 🧠 Introduction

Understanding human emotions through voice enables more natural human-computer interaction. This project focuses on recognizing emotional states like happy, sad, angry, etc., from speech using MFCC features and machine learning.

---

## ✅ Features

- Upload audio files in various formats (WAV, MP3, OGG, FLAC)
- Converts non-WAV formats to WAV for processing
- Extracts MFCC features from audio
- Predicts emotion using a trained Random Forest model
- Clean, intuitive UI built with Streamlit

---

## 🛠 Tech Stack

- **Language**: Python
- **Libraries**:
  - `librosa` – audio feature extraction
  - `scikit-learn` – model training and evaluation
  - `joblib` – model serialization
  - `streamlit` – web app deployment
  - `pydub` – audio format conversion
- **Model**: Random Forest Classifier
- **Deployment**: Streamlit App (local or cloud)

---

## 📁 Dataset

- **RAVDESS Dataset** (Ryerson Audio-Visual Database of Emotional Speech and Song)
- Link: https://zenodo.org/record/1188976
- Emotions covered: Neutral, Calm, Happy, Sad, Angry, Fearful, Disgust, Surprised

---

## 🧩 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/voice-emotion-detector.git
   cd voice-emotion-detector

---

## 🚀 Usage
Upload or record a voice sample.

The system will convert the file to WAV if necessary.

MFCC features are extracted and passed to the trained model.

Predicted emotion is displayed on the screen.

---

##📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

