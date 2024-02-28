Face Detector
This is a simple face detection application built with Python, OpenCV, dlib, and tkinter. It allows users to detect faces either from a live video stream captured by the computer's camera or from uploaded video files.

Features
Detect faces in real-time using the computer's camera.
Upload video files (supports .mp4 and .avi formats) for face detection.
Utilizes the dlib library for face detection.
Provides a graphical user interface using tkinter.
Requirements
Python 3.x
OpenCV
dlib
tkinter
Pillow (PIL)
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your_username/face-detector.git
Install the required dependencies:

bash
Copy code
pip install opencv-python-headless dlib pillow
Usage
Run the face_detector.py script:

bash
Copy code
python face_detector.py
Choose between the "Video Camera" option to use the computer's camera for real-time face detection or the "Upload Video" option to select a video file from your system.

Once the application is running, faces will be detected and outlined in the video stream or uploaded video.

Contributions
Contributions are welcome! If you find any issues or would like to contribute enhancements, feel free to open an issue or create a pull request.

License
This project is licensed under the MIT License.
