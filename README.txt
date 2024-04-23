# Facedetector

Face Recognition Application
This application uses Python, Tkinter, PIL, face_recognition, and DeepFace libraries to detect faces in images, draw rectangles around detected faces, and perform deep learning analysis to estimate attributes such as age, emotion, gender, and race.

Features
Load images from your local drive.
Detect faces in the images.
Display the detected faces with red rectangles.
Analyze detected faces to estimate age, emotion, gender, and race.
Count and display the number of faces detected.
Installation
Before running the application, you must install the required Python libraries. You can install these libraries using pip:

bash

pip install tkinter PIL face_recognition numpy deepface

Usage
To use the application, follow these steps:

Run the application script:
bash
Copy code
python face_recognition_app.py
Click on the "Load Image" button to select an image file from your computer.
The application will display the image with detected faces outlined in red.
Results from the analysis of each detected face will be printed in the console, including estimated age, dominant emotion, gender, and race.
Requirements
Python 3.8 (or less)
Tkinter (usually comes with Python)
PIL (Pillow)
face_recognition
NumPy
DeepFace
Contributing
Contributions to this project are welcome! To contribute:

Fork the repository.
Create a new branch for your feature (git checkout -b feature/new-feature).
Commit your changes (git commit -am 'Add some new-feature').
Push to the branch (git push origin feature/new-feature).
Open a new Pull Request.
