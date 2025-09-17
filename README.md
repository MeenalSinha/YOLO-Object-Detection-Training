# 🎯 Object Detection and Training with YOLO

## 📌 Overview

The **Object Detection Project** demonstrates how to detect and classify objects in images using the **YOLO (You Only Look Once)** deep learning framework. This notebook provides a complete workflow from model setup to real-time predictions on images and video streams.

The project is built in **Python (Jupyter Notebook/Colab)** and leverages popular computer vision and deep learning libraries for training, evaluation, and inference.

---

## 🚀 Features

* Pre-trained YOLO model loading (e.g., YOLOv5/YOLOv8)
* Object detection on images and video
* Bounding box visualization with labels & confidence scores
* Dataset handling & preprocessing
* Model evaluation on custom data
* Real-time inference support

---

## 🛠 Technologies Used

* **Python 3.x**
* **OpenCV** → Image handling & visualization
* **PyTorch / Ultralytics YOLO** → Deep learning framework
* **Matplotlib** → Result plotting
* **Google Colab** → Easy training & GPU support

---

## ⚙ Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/MeenalSinha/YOLO-Object-Detection-Training.git
   cd YOLO-Object-Detection-Training
   ```

2. **(Optional) Create virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate      # On Windows
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

---

## ▶ Usage

* Open the project in **Google Colab**:
  [YOLO\_Object\_Detection\_&\_Training\_Bootcamp.ipynb](https://github.com/MeenalSinha/YOLO-Object-Detection-Training/blob/main/YOLO_Object_Detection_%26_Training_Bootcamp.ipynb)

* Run the notebook step by step:

  1. Install YOLO and required libraries
  2. Load pre-trained YOLO model
  3. Run inference on sample images
  4. Visualize bounding boxes with labels
  5. Test with custom image/video uploads
  6. (Optional) Fine-tune YOLO on custom dataset

---

## 📊 Example Workflow

1. Import YOLO model with PyTorch
2. Load dataset (COCO/custom images)
3. Run detection → generate bounding boxes & confidence scores
4. Visualize results using OpenCV/Matplotlib
5. Export model outputs for downstream tasks

---

## 👨‍💻 Author

**Meenal Sinha**

* 📧 [meenal.sinha09@gmail.com](mailto:meenal.sinha09@gmail.com)

---
