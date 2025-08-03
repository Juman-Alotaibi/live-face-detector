# live-face-detector
Real-time face detection using OpenCV and Haar cascades. Detects faces from webcam input and highlights them with green rectangles. Works with human and cartoon faces.
💻 Features
Detects faces in real-time using webcam

Draws a green bounding box around each detected face

Can detect cartoon/anime faces as well

Written in pure Python using OpenCV

🧠 How it works
The script uses OpenCV’s built-in Haar Cascade face detector.

Each video frame is converted to grayscale.

Faces are detected using detectMultiScale() and drawn on top of the original image using cv2.rectangle().

🚀 Requirements
Python 3.x
OpenCV
▶️ How to Run
Clone this repository.
Make sure your webcam is connected.
Run the script:

