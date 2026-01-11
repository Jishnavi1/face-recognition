Face Recognition Attendance Tracker System
A smart attendance system built with Python, OpenCV, and Tkinter that uses real-time face recognition to automate student attendance tracking.

📌 Project Overview
This application captures faces through a webcam, recognizes registered users using face encoding, and logs attendance automatically with time and date. It's designed to enhance efficiency and eliminate manual entry errors in academic or workplace settings.

🛠️ Technologies Used
Python 3
OpenCV
Tkinter (GUI)
face_recognition (dlib)
NumPy
Datetime & OS Libraries
🚀 Features
Real-time face detection and recognition using webcam.
GUI interface built with Tkinter for ease of use.
Attendance recorded with timestamp into a CSV file.
Handles edge cases like poor lighting and partial face visibility.
Basic exception handling and logging for stability.
📂 Project Structure
face_recognition/
├── photos/
│   ├── se.jpg
│   ├── pm.jpg
│   └── cm.jpg
├── attendance_system.py
├── YYYY-MM-DD.csv
└── README.md
