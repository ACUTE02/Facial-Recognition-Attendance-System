# Facial Recognition Attendance System
# 📌 Overview
The Facial Recognition Attendance System is a Python-based project that automates the attendance process using facial recognition. 
It provides a modern Tkinter GUI with gradient animations, text-to-speech support, and multiple modules for capturing student images, training a face recognition model, 
marking attendance automatically, and viewing attendance reports.
This project is designed for educational institutions to replace manual roll-call or register systems with a secure and efficient attendance tracker.

# ✨ Features

🎥 Face Capture & Registration – Register new students with Enrollment Number & Name.

🤖 Model Training – Train facial data using LBPH Face Recognizer from OpenCV.

📋 Automatic Attendance – Recognize faces in real-time and mark attendance with timestamp.

📊 Attendance Reports – View detailed attendance summaries per subject.

📝 Manual Attendance Entry – Option to manually fill attendance if needed.

🔊 Text-to-Speech Feedback – Provides audio guidance during usage.

🎨 Modern GUI – Animated gradient background, interactive buttons, and responsive design.

# 🏗️ Project Structure
# Facial-Recognition-Attendance-System
- **attendance.py:**          Main GUI application (modern dashboard)
- **show_attendance.py:**     Module to view and summarize attendance
- **trainImage.py:**          Module to train images using LBPH recognizer
- **takemanually.py:**        Module for manual attendance entry
- **test.py:**                Test script to fetch camera feed (via IP/webcam)
- **TrainingImage:**          Captured student face images
- **TrainingImageLabel:**     Trained model (YAML file)
- **StudentDetails:**         CSV with student enrollment & names
- **Attendance:**             Stored attendance records (per subject & date)
- **haarcascade_frontalface_default.xml:** Haar Cascade for face detection
- **requirements.txt:**       Dependencies list
- **README.md:**              Documentation (this file)

# 🛠️ Technologies Used

**Language:** Python 3.x

**Libraries:** OpenCV (face detection, recognition)NumPy, Pandas (data handling)Pillow (image processing)Tkinter (GUI)pyttsx3 (text-to-speech)Requests (for IP camera testing)

**Algorithm:** LBPH (Local Binary Pattern Histogram) Face Recognizer

# ⚙️ Installation 
Prerequisites
Python 3.7+
Webcam or IP Camera

# 🚀 Usage
**Register Student**

**Enter Enrollment No & Name → Capture Images.**

**Train the model after capturing images.**

**Take Attendance**

**Start automatic face recognition.**

**Recognized students will have attendance marked with date & time.**

**View Attendance**

**Choose subject → View attendance records & summary reports.**

**Manual Attendance (Optional)**

**Run takemanually.py to fill attendance manually if required.**

**Test Camera Feed**

**Run test.py to check camera connection (supports IP/webcam).**

