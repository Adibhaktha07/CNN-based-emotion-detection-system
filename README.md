# 😊 CNN-Based Real-Time Emotion Detection System

This project is a real-time facial emotion detection system using a Convolutional Neural Network (CNN) model built with Keras and OpenCV. It captures live video from your webcam, detects faces, and classifies emotions such as Happy, Sad, Angry, Surprise, and more.

---

## 📌 Features

- 🎥 Real-time face detection using Haar cascades
- 😊 Emotion classification using a pre-trained CNN model
- 📊 7 emotion classes: Angry, Disgust, Fear, Happy, Neutral, Sad, Surprise
- 🧠 Model trained on the FER-2013 dataset (or similar)
- 🖥️ Simple OpenCV interface for visualization

---

## 🛠️ Tech Stack

- **Python**
- **OpenCV**
- **Keras** (with TensorFlow backend)
- **NumPy**

---

## 📂 Folder Structure
emotion-detection/

│
├── haarcascade_frontalface_default.xml # Haar Cascade for face detection

├── model.h5 # Pre-trained CNN model

├── emotion_detector.py # Main Python script

├── requirements.txt # Python dependencies

└── README.md # Project description

## 🚀 Getting Started

### 1. Clone the Repository

```
git clone https://github.com/Adibhaktha07/emotion-detection.git
cd emotion-detection

2. Install Dependencies
Ensure you have Python 3.7+ installed. Then install required packages:

pip install -r requirements.txt

3. Run the Application
python emotion_detector.py
Press q to close the window.

📦 Requirements
Create a requirements.txt file with:
Copy
Edit
opencv-python
tensorflow
keras
numpy

😊 Emotion Classes
The model can detect the following emotions:

Angry 😠
Disgust 🤢
Fear 😨
Happy 😄
Neutral 😐
Sad 😢
Surprise 😲

🧠 Model Training (Optional)
If you want to train your own emotion detection model:
Download the FER-2013 dataset
Preprocess the data (resize to 48x48 grayscale images
Build a CNN using Keras
Train and validate the model
Save it as model.h5

🖼️ Demo
Add your own GIF or image demo here (optional)

# Example (once uploaded to GitHub):
![Demo](https://github.com/Adibhaktha07/emotion-detection/blob/main/demo.gif)

🙋‍♂️ Author
Adithya Bhaktha
