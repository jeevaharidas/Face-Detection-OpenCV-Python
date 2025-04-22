# Face Detection using OpenCV and Python

This project is a simple and effective **Face Detection** system built using **OpenCV** and **Python**.  
It uses a **Haar Cascade Classifier** to detect faces from a live webcam feed in real-time.  
A great starting point for beginners learning about Computer Vision!

## Features
- Real-time face detection using webcam
- Detects multiple faces in a single frame
- Draws bounding boxes around detected faces
- Lightweight and easy to set up

## Technologies Used
- Python
- OpenCV
- Haar Cascade Classifier (Pre-trained XML model)

## How to Run
1. Clone the repository.

2. Make sure the following file is available:
   - `Resources/haarcascade_frontalface_default.xml`

3. Install OpenCV:
   ```bash
   pip install opencv-python

4. Run the script:
   ```bash
   python face_detection.py

# Output
The webcam will open and start detecting faces.
Detected faces will be highlighted with a bounding box in real-time.
