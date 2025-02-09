# Face-Recognition-Based-Attendance-System
This Flask-based face recognition attendance system automates attendance tracking using OpenCV, scikit-learn, and joblib. It detects faces in real-time, recognizes registered users, and logs attendance with timestamps. The system supports adding new users and retraining the model dynamically.
🔹Features
Real-time face detection & recognition using OpenCV.
Automated attendance marking with timestamps.
CSV-based attendance records for easy tracking.
Dynamic user registration with live image capture.
Flask web interface for easy interaction.
Model retraining whenever new users are added.
🔹 Technologies Used
Backend: Python, Flask
Computer Vision: OpenCV, NumPy
Machine Learning: K-Nearest Neighbors (KNN), scikit-learn, joblib
Data Storage: Pandas, CSV
🔹 How It Works
Register Users: Capture and store face images via /add.
Start Attendance: Detect faces and log attendance via /start.
View Attendance: Records are saved in Attendance/.
🔹 Future Improvements: Upgrade to deep learning models (e.g., FaceNet) for better accuracy.

🚀 Contributions welcome!
