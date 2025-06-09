#    Face-Recognition-Based-Attendance-System

Attendance Management System based on Face Recognition using Python and OpenCv  


# 📌 Project Overview
The Face Recognition Based Attendance System is an AI-powered application that automates attendance tracking using facial recognition. 
It replaces traditional manual or biometric systems by identifying and verifying individuals through a live camera feed or image input, recording their attendance securely and efficiently.

#   🎯 Features

✅ Real-time face detection and recognition

📷 Camera-based image capture

🧠 Machine learning model training with face encodings

📁 Student/employee image dataset management

🕒 Automatic date and time logging

🗂️ CSV/Database-based attendance records

🔒 Secure and contactless system

💻 User-friendly interface (CLI or GUI)


#   🔧 Technologies Used

Python 3.x

OpenCV – Image processing

face_recognition – Facial feature extraction and matching

NumPy – Numerical computations

Pandas – Attendance data management

Tkinter / Flask (optional) – GUI or web interface

SQLite / CSV – Storage backend


#  What steps you have to follow??

- Download my Repository
- Create a TrainingImage folder in a project.
- Open a AMS_Run.py and change the all paths with your system path
- Run AMS_Run.py.


#    Project Structure

- After run you need to give your face data to system so enter your ID and name in box than click on 'Take Images' button.
  
- It will collect 50+ images of your faces, it save a images in 'TrainingImage' folder.
  
- After that we need to train a model(for train a model click on 'Train Image' button).
  
- It will take 1-2 minutes for training(for 1 person data).
  
- After training click on 'Automatic Attendance', it can fill attendance by your face using our trained model (model will save in 'TrainingImageLabel').
  
- it will create system '.csv' file of attendance according to time & subject.
  
- You can store data in database (install wampserver),change the DB name according to your in 'AMS_Run.py'.
  
- "Manually Fill Attendance" Button in UI is for fill a manually attendance (without face recognition),it's also create a '.csv' and store in a database.


#   🛡️ Security & Privacy

All facial data is stored and processed locally. Ensure compliance with data protection regulations if used in a real-world environment.

