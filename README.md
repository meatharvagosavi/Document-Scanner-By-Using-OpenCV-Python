# 📄 Document Scanner using OpenCV

A real-time **Document Scanner** built using **Python** and **OpenCV** that detects documents from webcam input or images, applies perspective transformation, and generates a scanned version similar to mobile scanning applications like CamScanner.

---

## 🚀 Features

* 📷 Real-time webcam document detection
* 🖼️ Scan documents from images
* 🔍 Edge and contour detection using OpenCV
* 📐 Perspective transformation for top-down view
* 🎚️ Adjustable threshold values using trackbars
* 🧾 Adaptive thresholding for scanned effect
* 💾 Save scanned documents with a single key press

---

## 🛠️ Technologies Used

* Python 3.x
* OpenCV
* NumPy

---

## 📂 Project Structure

```bash
Document-Scanner/
│
├── main.py           # Main application
└── README.md
```

---

## ⚙️ Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/document-scanner-opencv.git
cd document-scanner-opencv
```

2. Install dependencies:

```bash
pip install opencv-python numpy
```

---

## ▶️ Run the Project

For webcam scanning:

```bash
python main.py
```

To scan from an image:

```python
webCamFeed = False
pathImage = "1.jpg"
```

---

## 🎮 Controls

| Key   | Function              |
| ----- | --------------------- |
| **s** | Save scanned document |

Saved documents will be stored inside the **Scanned/** folder.

---

## 🔍 Working Principle

1. Capture image from webcam or file.
2. Convert image to grayscale.
3. Apply Gaussian Blur and Canny Edge Detection.
4. Detect contours and find the largest quadrilateral.
5. Apply Perspective Transformation.
6. Perform Adaptive Thresholding.
7. Save the scanned output.

---

## 📸 Output

The application displays:

* Original Image
* Grayscale Image
* Thresholded Image
* Contours
* Detected Document
* Warped Perspective
* Final Scanned Output

---

## 🌟 Future Improvements

* Automatic document cropping
* PDF export functionality
* OCR integration using Tesseract
* Batch document scanning

---

## 👨‍💻 Author

**Atharva Gosavi**

If you like this project, don't forget to ⭐ the repository!

---

✨ *Transform your webcam into a powerful document scanner using OpenCV!*
