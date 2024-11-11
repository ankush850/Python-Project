# Computer Vision Road & Lane Detection

<p align="center">
<a href="https://github.com/ankush850"><img src="https://img.shields.io/static/v1?logo=github&label=maintainer&message=ankush850&color=blue" alt="Maintainer"/></a>
<a href="https://github.com/ankush850/Data-Analyst-Mini-Projects"><img src="https://img.shields.io/badge/Status-Complete-brightgreen" alt="Status"/></a>
</p>

## 📌 Project Overview
An image processing and computer vision project using **OpenCV** to perform lane and road boundary detection from vehicular camera feeds.

The algorithm handles edge detection across various visibility and lighting conditions by applying region-of-interest masking, edge filters (Canny, Sobel, Laplacian), and Hough transform lane marking.

---

## ✨ Features
- **Region of Interest (ROI) Masking**: Isolates the driving lane corridor.
- **Multi-Filter Edge Detection**:
  - Canny Edge Detection
  - Sobel X & Y gradients
  - Laplacian 2nd derivative filtering
- **Visual Colorization**: Overlays detected lane boundaries onto the original highway image.

---

## 📦 Requirements & Installation
Install the project dependencies:

```bash
pip install -r requirements.txt
```

### Dependencies
- `opencv-python` - Computer vision and image transformation pipeline
- `matplotlib` - Visualization of intermediate filtered matrices
- `numpy` - Matrix operations and masking
- `jupyter` - Interactive notebook execution

---

## 🚀 How to Run
Open and execute the notebook:

```bash
jupyter notebook 020_Road_Detection.ipynb
```
