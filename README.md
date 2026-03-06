# AI Sign Language Translator for Deaf and Mute Communication

## 📖 Project Overview
This project develops an AI-powered system that recognizes sign language gestures from images and converts them into text and speech. The goal is to help deaf and mute individuals communicate more easily using artificial intelligence.

The system uses a Convolutional Neural Network (CNN) trained on the ASL Alphabet dataset to detect hand gestures representing letters. Once a gesture is recognized, the predicted letter is converted into speech using Google's Text-to-Speech (gTTS) library.

---

## 🎯 Objectives

- Recognize sign language gestures using deep learning
- Convert detected gestures into readable text
- Convert text output into speech
- Demonstrate how AI can improve accessibility for deaf and mute individuals

---

## 🧠 Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- gTTS (Google Text-to-Speech)
- Matplotlib
- Scikit-learn

---

## 🗂 Project Structure

sign-language-translator-ai

│

├── model/

│ └── sign_language_model.h5

│

├── images/

│ ├── hand gesture.jpeg

│ └── download.png

│

├── audio/

│ └── output-final.mp3

│

├── notebooks/

│ └── Gen_AI_model_for_deaf_and_mute.ipynb

│

├── requirements.txt

├── README.md

└── .gitignore


---

## 📊 Dataset

This project uses the **ASL Alphabet Dataset** which contains images representing American Sign Language hand gestures.

Dataset contains:

- 87,000 images
- 29 classes
- Alphabets A–Z
- Special symbols: space, delete, nothing

Dataset source:
https://www.kaggle.com/datasets/grassknoted/asl-alphabet

---

## ⚙️ Model Architecture

The system uses a Convolutional Neural Network (CNN) to classify hand gestures.

Architecture:

Input Image (64x64)
↓  
Conv2D Layer  
↓  
MaxPooling Layer  
↓  
Conv2D Layer  
↓  
MaxPooling Layer  
↓  
Flatten Layer  
↓  
Dense Layer  
↓  
Output Layer (29 classes)

---

## 🔄 Workflow

The pipeline of the system works as follows:

Hand Gesture Image  
↓  
Image Preprocessing (OpenCV)  
↓  
CNN Model Prediction  
↓  
Letter Classification  
↓  
Text Output  
↓  
Speech Output using gTTS

---

## 🧪 Example Output

Input Image:

Hand gesture representing a sign

Predicted Output:

Predicted Sign: hello


Speech Output:

Audio generated saying the predicted letter.

---

## 💻 Installation

Clone the repository:

git clone https://github.com/darshinio-debug/sign-language-translator-ai.git

Navigate to the project folder:

cd sign-language-translator-ai

Install dependencies:
pip install -r requirements.txt


---

## ▶️ Running the Project

Run the prediction script:
Gen AI model for deaf and mute.ipynb


The system will:

1. Load the trained CNN model
2. Process the input image
3. Predict the sign language letter
4. Convert the prediction to speech

---

## 🚀 Future Improvements

Possible improvements for this project:

- Real-time sign detection using webcam
- Hand tracking using MediaPipe
- Sentence generation from multiple gestures
- Streamlit web interface for live translation
- Mobile application integration

---

## 🌍 Real World Applications

- Communication support for deaf and mute individuals
- Educational tools for learning sign language
- Accessibility systems in hospitals and public services
- AI-based assistive technologies

---

## 👩‍💻 Author

Darshini

AI / Machine Learning Enthusiast  
Focused on building AI solutions for accessibility and social impact.

---


