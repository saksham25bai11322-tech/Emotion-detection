# Face Detection Software

## Overview

This project is a simple real-time face detection system built using Python and OpenCV. It uses a pre-trained Haar Cascade classifier to detect human faces from a webcam feed and draws bounding boxes around them.

This project is designed for beginners in Artificial Intelligence and Machine Learning to understand the fundamentals of computer vision.

---

## Features

* Real-time face detection using webcam
* Lightweight and fast
* Easy to set up and run
* Beginner-friendly implementation

---

## Technologies Used

* Python
* OpenCV
* Haar Cascade Classifier

---

## Installation

### Step 1: Clone the repository

```
git clone https://github.com/your-username/face-detection-project.git
cd face-detection-project
```

### Step 2: Install dependencies

```
pip install opencv-python
```

---

## Usage

Run the following command:

```
python face_detection.py
```

* Your webcam will open automatically
* Faces will be detected and highlighted with rectangles
* Press **ESC** key to exit the application

---

## Project Structure

```
face-detection-project/
│
├── face_detection.py
└── README.md
```

---

## How It Works

1. The webcam captures live video frames
2. Each frame is converted to grayscale
3. Haar Cascade classifier detects faces
4. Rectangles are drawn around detected faces
5. Output is displayed in real-time

---

## Future Improvements

* Add face recognition
* Add emotion detection
* Save detected faces
* GUI interface

---

## License

This project is open-source and free to use for educational purposes.

---
