# 🕵️‍♂️ Real-time Human Silhouette Detection using YOLOv8

This project demonstrates real-time human silhouette detection using a webcam feed and the YOLOv8 segmentation model. The output displays only the segmented silhouettes from live video using OpenCV.

---

## 📸 Demo

<!-- Optional: Add a demo gif or screenshot here -->
![demo](demo.gif)

---

## 🚀 Features

- Real-time webcam capture
- Person segmentation using YOLOv8n-seg
- Silhouette mask creation and overlay
- Interactive video display using OpenCV

---

## 🛠️ Tech Stack

- Python
- OpenCV
- NumPy
- Ultralytics YOLOv8
- Jupyter Notebook

---

## 📦 Installation

1. **Clone the Repository**

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

⚠️ Troubleshooting
Webcam not accessible?

Make sure no other apps are using it.

Try changing cv2.VideoCapture(0) to another index like cv2.VideoCapture(1).

Use appropriate OpenCV backend: cv2.CAP_DSHOW, cv2.CAP_V4L2, etc.

Avoid running in Jupyter if webcam fails; try from a .py file.

