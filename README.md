🖐️ Sign Language to Text Conversion using Deep Learning

This project implements a real-time sign language to text conversion system using computer vision and deep learning.
It captures hand gestures through a webcam, recognizes the sign using a trained CNN model, and converts it into readable text—aimed at assisting speech- and hearing-impaired users.

📌 Features

Real-time hand gesture detection using webcam

CNN-based sign classification

Converts hand signs into corresponding text

Uses MediaPipe and OpenCV for accurate hand tracking

Lightweight and runs on CPU (no GPU required)

🛠️ Tech Stack

Python 3.10

TensorFlow / Keras

OpenCV

MediaPipe

CVZone

NumPy

Pillow

pyttsx3 (optional text-to-speech support)

📂 Project Structure


AI_AAC_Project/
   │
├── final_pred.py  # Main script for real-time prediction


├── cnn8grps_rad1_model.h5 # Trained CNN model


├── requirements.txt       # Project dependencies


├── README.md              # Project documentation


└── .venv/                 # Virtual environment (not pushed to GitHub)


⚙️ Installation & Setup


1️⃣ Clone the Repository
https://github.com/pavanbijili/Sign-To-Text-Conversion
cd AI_AAC_Project


2️⃣ Create & Activate Virtual Environment (Recommended)
py -3.10 -m venv .venv
.venv\Scripts\activate



You should see:



(.venv)


3️⃣ Install Required Libraries
pip install -r requirements.txt


▶️ How to Run the Project

Make sure your webcam is connected, then run:

python final_pred.py

The system will:

Open the webcam

Detect hand gestures

Predict the sign

Display the corresponding text in real time

📦 requirements.txt
numpy==1.26.4
tensorflow==2.16.1
tf-keras==2.16.0
opencv-python==4.5.5.64
cvzone==1.6.1
mediapipe==0.10.11
pyttsx3==2.90
pyenchant==3.2.2
Pillow==9.2.0
🧠 Working Principle (Brief)

Webcam captures live video frames

MediaPipe detects hand landmarks

Hand region is preprocessed and resized

CNN model predicts the sign class

Predicted sign is converted to readable text

🚀 Future Enhancements

Add dynamic (continuous) gesture recognition

Improve accuracy with larger datasets

Add full sentence construction

Integrate speech output for text

🙌 Acknowledgements

Open-source GitHub implementations for sign recognition

TensorFlow & MediaPipe documentation

CVZone hand tracking utilities

📜 Disclaimer

This project is developed for educational and academic purposes.
Model accuracy depends on lighting conditions, camera quality, and hand positioning.

⭐ If you like this project

Give it a star ⭐ and feel free to fork and improve it!
