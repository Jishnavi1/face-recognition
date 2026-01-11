# Face Recognition Attendance System

An automated attendance tracking system developed using Python, OpenCV, and face recognition that marks attendance in real time through a webcam.

# 📌 Project Overview

This project uses live camera input to detect and recognize predefined faces. When a known face is identified, the system marks attendance automatically with the current date and time in a CSV file. The system avoids duplicate entries by marking each person only once per session.

It is suitable for academic demonstrations and basic real-world attendance automation.

# 🛠️ Technologies Used

- Python 3

- OpenCV

- face_recognition (dlib)

- NumPy

- CSV, Datetime, OS Libraries

# 🚀 Features

- Real-time face detection and recognition using a webcam

- Automatic attendance recording with timestamp

- Date-wise CSV file generation

- Prevents duplicate attendance entries

- Simple and lightweight implementation

# 📂 Project Structure
face_recognition_attendance/
├── photos/
│   ├── se.jpg
│   ├── pm.jpg
│   └── cm.jpg
├── attendance_system.py
├── YYYY-MM-DD.csv
└── README.md
