# Secured Authentication Process for Physically Challenged People Using Morse Code and Machine Learning Algorithms

> A novel authentication system that combines Eye Tracking, Morse Code, Computer Vision, and Machine Learning to provide a secure and accessible login mechanism for physically challenged individuals.

## 📌 Overview

Traditional authentication methods such as passwords, PINs, and biometric systems can be challenging for users with physical disabilities. This project introduces an innovative authentication framework where users enter passwords through eye blinks encoded as Morse Code.

The system detects facial landmarks and eye movements in real time using computer vision techniques. Eye blinks are translated into Morse code symbols (`.` and `-`), which are then converted into numeric passwords for authentication.

## ✨ Features

- 👁️ Real-time Eye Tracking
- 🔐 Morse Code-based Password Authentication
- 🤖 Face Recognition using Machine Learning
- ♿ Accessibility-focused Design
- 🛡️ Enhanced Security against Shoulder Surfing
- 🔄 Password Recovery Mechanism
- 📷 Webcam-based Authentication
- ⌨️ Virtual Morse Code Keyboard

## 🏗️ System Architecture

```text
User
  │
  ▼
Webcam Capture
  │
  ▼
Face Detection (Haar Cascade)
  │
  ▼
Facial Landmark Detection (Dlib)
  │
  ▼
Eye Aspect Ratio (EAR)
  │
  ▼
Blink Detection
  │
  ▼
Morse Code Generation
  │
  ▼
Password Verification
  │
  ▼
Authentication Success/Failure
```

## 🛠️ Technologies Used

- Python 3.8
- OpenCV
- Dlib
- Tkinter
- Pandas
- PyQt5
- LBPH Face Recognition

## 📂 Project Structure

```text
Secured-Authentication-Using-Morse-Code/
│
├── dataset/
├── models/
├── gui/
├── authentication/
├── database/
├── main.py
├── requirements.txt
└── README.md
```

## 📋 Installation

```bash
git clone https://github.com/mpranav38/Secured-Authentication-Process-for-Physically-Challenged-People-Using-Morse-Code-and-ML-Algorithms.git

cd Secured-Authentication-Process-for-Physically-Challenged-People-Using-Morse-Code-and-ML-Algorithms
```

```bash
pip install -r requirements.txt
```

## ▶️ Usage

### Register User

1. Launch the application.
2. Select Register.
3. Enter Username, Password, and Recovery Keyword.
4. Capture face images using the webcam.
5. Train the face recognition model.

### Login

1. Enter Username.
2. Webcam activates.
3. Face is recognized.
4. Enter Morse code password using eye blinks.
5. Authentication is verified.

## ⚠️ Limitations

- Requires sufficient lighting.
- Dark sunglasses may affect detection.
- Longer passwords take more time.
- Users with severe eye impairments may face challenges.

## 🔮 Future Enhancements

- Voice-based username entry.
- Night vision camera support.
- Improved low-light detection.
- Support for sunglasses.
- Faster Morse code input.
- Deep Learning-based facial recognition.

## 👨‍💻 Authors

- Pranav M
- Abhishek N
- Sathvik K C
- Mansi D

Department of Information Science & Engineering  
Jain University, Bangalore, India

## 📄 License

This project is developed for academic and research purposes.

⭐ If you found this project useful, consider giving it a star on GitHub!




