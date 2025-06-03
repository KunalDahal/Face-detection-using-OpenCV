# Real-Time Face Detection using OpenCV and Haar Cascades

This Python application uses OpenCV and Haar Cascade Classifiers to perform real-time face detection from a webcam feed.

## 🔧 Requirements

- Python 3.x
- OpenCV

Install OpenCV using pip:
```bash
pip install opencv-python
```

## 📁 Files

- `face_detection.py`: Main Python script.
- `haarcascade_frontalface_default.xml`: Haar Cascade classifier for face detection (must be in the same directory).

## ▶️ How to Run

```bash
python face_detection.py
```

Press **Q** to exit the webcam window.

## 📷 Features

- Uses OpenCV’s `CascadeClassifier` to detect faces.
- Displays real-time webcam feed with rectangles drawn around detected faces.
- Shows a counter of the number of faces detected.

## 💡 Notes

Make sure you have the `haarcascade_frontalface_default.xml` file in the same directory. You can download it from:
[OpenCV GitHub - Haar Cascades](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml)
