# Face-Attendance-Recognition-System

Facial recognition based attendance web application, designed for universities and to be used by students and teachers. Students can register their attendance by taking a photo through their device's camera, which will be validated by a machine learning model in real time; they can also register in the system to be added to the database. Teachers can access attendance reports, analysis and metrics through a dashboard. The system is developed to integrate with a real-time database, ensuring accurate and efficient attendance management.


## Main Functionalities:
- User Registration: Authentication system that allows differentiated access for students and teachers.
- Attendance Capture:
  - Students can activate the camera, capture their photo, and the system validates their identity with the facial recognition model.
  - If the system correctly identifies the student, it automatically registers their attendance.
  - The photo is stored in a data lake and, upon reaching 20 photos, the oldest photos are managed to avoid overfitting the model.
- Dashboard for Teachers:
  - Teachers can access a visual analysis of the group's attendance (dashboard)
  - Download weekly or monthly reports
  - View in real time the daily attendance list.

## Technologies Used:
- Frontend: HTML/CSS, JavaScript for custom interface and image capture.
- Backend: Flask/Django (Python) for API and data processing.
- Facial Recognition: Amazon Rekognition for facial detection and authentication, or custom alternative with OpenCV and TensorFlow.
- Data Lake: Amazon S3 for real-time photo storage.
- Database: Amazon RDS (PostgreSQL) for attendance, user and configuration data management.
- Data Visualization: Chart.js or D3.js for interactive charts on the dashboard.

## System Requirements:
Python 3.8+
Dependencies:
Install with: pip install -r requirements.txt
AWS credentials for Amazon Rekognition and S3.

## User manual
LINK AL PDF PARA Q ESTE BIEN EXPLICADO
