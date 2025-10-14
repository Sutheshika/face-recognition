🧠 Face Recognition System

This project is a real-time face recognition system built using Python and OpenCV.
It can detect and recognize human faces through a webcam.
The system has two main parts — one for training and another for recognition.

train_data.py – Captures face images using a webcam and saves them in a dataset folder.

face_recognition.py – Trains the model with saved images and recognizes faces in real-time.

Features:

Detects and recognizes faces using a webcam

Displays names for known faces

Marks unknown persons

Uses Haar Cascade and FisherFaceRecognizer

Technologies Used:

Python

OpenCV

NumPy

How to Run:

Run train_data.py to capture images

Run face_recognition.py to recognize faces
