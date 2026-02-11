# Face Detection using OpenCV

## 📌 Project Overview

This project implements real-time face detection using OpenCV and Haar Cascade classifiers.
The system captures video from a webcam and detects faces frame-by-frame.

The detected faces are highlighted with bounding boxes in the output window.

## 🛠 Technologies Used

* Python
* OpenCV
* Matplotlib
* Haar Cascade Classifier
* Anaconda (Python environment management)
* Visual Studio Code (IDE)

---

## 📂 Project Structure

```
face-detection/
│
├── face_detection.ipynb
├── haarcascade_frontalface_default.xml
└── README.md
```

---

## ⚙️ Requirements

Make sure you have the following installed:

* Python (via Anaconda)
* OpenCV
* Matplotlib
* NumPy

You can install required libraries using:

```bash
pip install opencv-python matplotlib numpy
```

or using conda:

```bash
conda install opencv matplotlib numpy
```

---

## ▶️ How to Run

1. Activate your Anaconda environment.
2. Open the project folder in Visual Studio Code.
3. Ensure the file `haarcascade_frontalface_default.xml` is in the project directory.
4. Run the notebook (`face_detection.ipynb`).
5. Press **'q'** to exit the webcam window.

---

## 🧠 How It Works

* The webcam captures live video frames.
* Each frame is converted to grayscale.
* The Haar Cascade classifier detects faces.
* Bounding boxes are drawn around detected faces.
* The result is displayed in real time.

---

## 📸 Output

* Real-time face detection window
* Captured frame displayed using Matplotlib

---

## 🚀 Future Improvements

* Add eye detection
* Add smile detection
* Improve detection accuracy using deep learning
* Convert notebook into a standalone Python script

---

## 👤 Author

Rohan Saha


