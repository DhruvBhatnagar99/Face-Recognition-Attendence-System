# Real Time Attendance System using Face Recognition

This program is designed to recognize faces and mark attendance for students automatically using face recognition technology. It uses the OpenCV and face_recognition libraries to capture images from a webcam and compare them with known faces to recognize and mark attendance.

Requirements:
1. Python 3.x
2. OpenCV
3. face_recognition
4. numpy


Installation:
1. Install Python 3.x from the official website.
2. Install OpenCV library by running the command pip install opencv-python.
3. Install face_recognition library by running the command pip install face-recognition.
4. Install numpy library by running the command pip install numpy.
5. Clone or download this repository.
6. Save images of students to be recognized in the "faces" folder with their names as the filename.


Usage:
1. Open the terminal and navigate to the downloaded repository directory.
2. Run the command python attendance.py to start the program.
3. The program will automatically capture frames from the webcam and compare them with the known faces.
4. If a recognized face is detected, the program will mark the attendance in a CSV file with the date as the filename and the name and time of the student.
5. The program will also display the webcam output with the name of the recognized person.


Conclusion:

This Real Time Attendance System using Face Recognition can be used by educational institutions or organizations to automate the attendance marking process and save time. However, this is just a basic implementation and can be further improved with additional features and accuracy.
