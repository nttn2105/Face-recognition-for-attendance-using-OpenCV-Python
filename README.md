📸 Face Recognition Attendance System using OpenCV and Python
This project implements an automated face recognition-based attendance system using OpenCV and Python. It captures faces through a webcam, recognizes them using a trained model, and logs attendance in real time.

🧰 Key Features
Face Detection: Uses Haar Cascade classifiers to detect faces in video streams.

Face Recognition: Implements Local Binary Pattern Histogram (LBPH) for recognizing known faces.

Attendance Logging: Records attendance with timestamps in a CSV file.

Simple GUI: Provides a basic user interface for interaction.

🛠️ Technologies Used
Programming Language: Python

Libraries: OpenCV, NumPy, Pandas

Models: Haar Cascade for detection, LBPH for recognition

🚀 How It Works
Data Collection: Capture multiple images of each person's face and store them.

Model Training: Train the LBPH recognizer with the collected face images.

Attendance: Run the system; it will detect and recognize faces, then log names and timestamps.

📂 Folder Structure
data/: Contains collected face images.

trainer/: Stores the trained face recognition model.

attendance.csv: CSV file with recorded attendance data
