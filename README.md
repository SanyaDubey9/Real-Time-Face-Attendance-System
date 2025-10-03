📌 Overview
This project is a Real-Time Face Attendance System developed using Python, OpenCV, and the face_recognition library. It automates the process of marking attendance by detecting and recognizing faces via webcam and logs the data automatically in a CSV file.

🚀 Features

✅ Real-time face detection using OpenCV

✅ Face recognition with high accuracy (using face_recognition built on dlib)

✅ Contactless & automated attendance logging

✅ Tkinter-based GUI for user-friendly interaction

✅ Attendance stored in CSV with Name, Date, and Time

🛠️ Tech Stack

Language: Python

Frontend: Tkinter (GUI)

Libraries: OpenCV, face_recognition, NumPy, Pandas, datetime

Backend: CSV file storage

IDE/Platform: Anaconda (Spyder/Jupyter)

📂 Project Structure
├── AMS_Run.py          # Main application file
├── training.py         # Train model with captured images
├── testing.py          # Test recognition
├── retrain.py          # Retrain model if needed
├── Attendance/         # Folder containing attendance CSV files
├── TrainingImage/      # Captured face images
├── trainer.yml         # Trained model file
└── README.md           # Project documentation

⚙️ How It Works

Register User – Capture and store face images.

Train Model – Train the recognizer using collected images.

Real-Time Detection – Webcam detects and recognizes registered faces.

Mark Attendance – Logs Name, Date, and Time into Attendance.csv.

▶️ Installation & Usage

Clone the repository:

git clone https://github.com/SanyaDubey9/face-attendance-system.git
cd face-attendance-system


Install dependencies:

pip install opencv-python face_recognition numpy pandas


Run the application:

python AMS_Run.py

📊 Sample Output

GUI dashboard for training and recognition

Real-time detection with bounding boxes around faces

Attendance logged in CSV as:

Name	Date	Time
Sanya	2025-08-04	10:32:41
🌟 Future Enhancements

Integration with SQL databases instead of CSV
Cloud-based storage for centralized attendance
Mobile app for remote access
Mask detection support
