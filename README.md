# 🔷 OpenCV Shape Detection

<p align="center">
  <b>A Computer Vision project for detecting and classifying geometric shapes using Python and OpenCV.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV">
  <img src="https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/github/license/saniartalaei/OpenCV-Shape-Detection?style=for-the-badge" alt="License">
</p>

---

## 📌 Overview

**OpenCV Shape Detection** is a classical Computer Vision project built with **Python and OpenCV** for detecting and classifying geometric shapes in images.

The project analyzes image contours and geometric properties to identify different shapes such as:

* 🔺 Triangle
* ⬛ Square
* ▭ Rectangle
* ⚪ Circle

Instead of relying on deep learning models, the project demonstrates how fundamental image-processing and contour-analysis techniques can be used to solve a practical Computer Vision problem.

---

## ✨ Features

* 🔍 Detect geometric shapes from images
* 🧩 Classify detected shapes based on their geometric properties
* 📐 Analyze contours and polygon approximations
* 🖼️ Process images using OpenCV
* 🏷️ Label detected objects directly on the image
* ⚡ Lightweight and fast classical Computer Vision approach
* 📚 Simple structure suitable for learning and experimentation

---

## 🧠 Computer Vision Pipeline

The detection process follows a traditional Computer Vision pipeline:

```text
Input Image
     │
     ▼
Image Preprocessing
     │
     ▼
Grayscale / Thresholding
     │
     ▼
Contour Detection
     │
     ▼
Contour Approximation
     │
     ▼
Geometric Analysis
     │
     ▼
Shape Classification
     │
     ▼
Annotated Output
```

### 1. Image Preprocessing

The input image is prepared for further analysis using standard image-processing operations.

### 2. Contour Detection

OpenCV contours are used to identify the boundaries of objects in the image.

### 3. Polygon Approximation

The detected contours are approximated as polygons. The number and arrangement of vertices provide useful information for identifying geometric shapes.

### 4. Shape Classification

Based on contour characteristics and geometric properties, objects are classified into different shape categories.

### 5. Visualization

The detected shapes are annotated on the original image, making the results easy to interpret.

---

## 🛠️ Technologies

| Technology | Purpose                              |
| ---------- | ------------------------------------ |
| 🐍 Python  | Programming language                 |
| 👁️ OpenCV | Image processing and Computer Vision |
| 🔢 NumPy   | Numerical and array operations       |

---

## 📂 Project Structure

```text
OpenCV-Shape-Detection/
│
├── 📁 Resources/
│   └── Input images and project resources
│
├── 📄 ShapeDetector.py
│   └── Main shape detection implementation
│
├── 📄 requirements.txt
│   └── Project dependencies
│
└── 📄 README.md
    └── Project documentation
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/saniartalaei/OpenCV-Shape-Detection.git
```

### 2. Navigate to the project directory

```bash
cd OpenCV-Shape-Detection
```

### 3. Install the dependencies

```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

Run the main Python script:

```bash
python ShapeDetector.py
```

The program will process the provided image resources and perform shape detection and classification.

---

## 🖼️ Example

The system can identify common geometric shapes from an input image and annotate the detected objects.

### Input

```text
          ▲
        Triangle

     ┌─────────┐
     │         │
     │  Square │
     │         │
     └─────────┘

          ○
        Circle
```

### Output

The detected shapes are identified and labeled directly on the processed image.

> 💡 You can add screenshots or GIFs of your actual project output to the `Resources` directory and display them here.

For example:

```markdown
<p align="center">
  <img src="Resources/result.png" width="800">
</p>
```

---

## 🔬 Core Concepts

This project demonstrates several important Computer Vision concepts:

### Contour Detection

Contours represent the boundaries of objects in an image and are fundamental to many classical Computer Vision applications.

### Polygon Approximation

Contour approximation simplifies complex contours into polygonal representations, making it possible to analyze the number of vertices and infer the object's shape.

### Geometric Features

Geometric properties such as:

* Number of vertices
* Bounding boxes
* Aspect ratio
* Contour area

can be used to distinguish between different shapes.

---

## 🎯 Learning Objectives

This project was developed to explore practical applications of:

* Computer Vision fundamentals
* OpenCV image processing
* Contour detection
* Shape analysis
* Polygon approximation
* Geometric feature extraction
* Object classification using traditional Computer Vision techniques

---

## 🔮 Future Improvements

Possible extensions for this project include:

* 📹 Real-time shape detection using a webcam
* 🎨 Shape detection based on color
* 📏 Estimating object dimensions
* 🔄 Detecting rotated objects
* 🧠 Comparing classical methods with Machine Learning approaches
* 🤖 Integrating shape detection into a larger Computer Vision pipeline
* 📊 Adding quantitative detection statistics
* ⚡ Improving robustness against noise and different lighting conditions

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome!

If you would like to contribute:

```bash
# Fork the repository

# Create a new branch
git checkout -b feature/your-feature

# Commit your changes
git commit -m "Add your feature"

# Push the branch
git push origin feature/your-feature
```

Then open a Pull Request.

---

## 📜 License

This project is open-source. See the repository for licensing information.

---

## 👨‍💻 Author

### Sani Artalaei

Computer Vision & Artificial Intelligence Enthusiast

Interested in:

* 🤖 Artificial Intelligence
* 👁️ Computer Vision
* 🧠 Deep Learning
* 🐍 Python
* 🔬 Medical Image Analysis
* 🖼️ Image Processing

---

<p align="center">
  <b>Built with ❤️ using Python & OpenCV</b>
</p>

<p align="center">
  ⭐ If you found this project useful, consider giving it a star!
</p>
