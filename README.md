# 👤 Real-Time Face Detection using OpenCV

This is a simple real-time face detection project using Python and OpenCV. It utilizes Haar Cascade Classifiers to detect faces from a webcam feed and draws green rectangles around any detected faces.

## 📸 Demo

![Face Detection Demo](demo.gif)  
*(Add a demo GIF or image of your project in action if you have one!)*

---

## 🧠 How It Works

This project uses OpenCV's built-in Haar cascade classifier:  
`haarcascade_frontalface_default.xml`, a pre-trained model for frontal face detection.

### Basic Workflow:
1. Capture video from webcam.
2. Convert each frame to grayscale.
3. Detect faces in the frame.
4. Draw a rectangle around detected faces.
5. Display the video with rectangles.
6. Exit on pressing the `q` key.

---

## 🧱 Requirements

Make sure you have the following installed:

- Python 3.x
- OpenCV (`cv2`)

### Install OpenCV:

```bash
pip install opencv-python
