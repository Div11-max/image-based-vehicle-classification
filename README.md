# Vehicle Classification System 🚗

An intelligent image-based vehicle classification system built using **OpenCV, YOLOv8, Feature Engineering, and XGBoost** to classify vehicles into **Hatchback, Sedan, and SUV** categories with **86.2% accuracy**.

---

## 📌 Overview

This project focuses on building a lightweight and efficient vehicle classification system using a single input image. Unlike traditional systems that rely on license plate recognition, this system identifies vehicle types directly from visual and geometric features.

The system is designed to work under real-world conditions such as:
- Occluded number plates
- Poor lighting
- Different camera angles
- Complex backgrounds

---

## 🚀 Features

- Automated dataset collection using web scraping
- Dataset cleaning and preprocessing
- YOLOv8-based quality filtering
- Image preprocessing pipeline:
  - Grayscale conversion
  - Gaussian Blur
  - CLAHE enhancement
  - Canny Edge Detection
- Feature extraction:
  - Hu Moments
  - GLCM Texture Features
  - HSV Color Analysis
  - Ground Clearance Detection
- XGBoost classification model
- Confidence-based correction system
- Gradio web interface deployment

---

## 🛠 Tech Stack

- Python
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- XGBoost
- YOLOv8
- Gradio
- Matplotlib
- Scikit-image

---

## 📂 Dataset

The dataset consists of vehicle images collected from web sources and organized into:

- Hatchback
- Sedan
- SUV

### Dataset preprocessing:
- Removed duplicate images
- Removed corrupted images
- Resized images to 224×224
- Normalized pixel values
- Filtered images using YOLOv8

---

## ⚙️ Project Pipeline

Input Image  
↓  
Preprocessing  
↓  
Segmentation  
↓  
Feature Extraction  
↓  
Feature Scaling  
↓  
SMOTE Balancing  
↓  
XGBoost Classification  
↓  
Confidence Correction  
↓  
Output Prediction

---

## 📊 Model Performance

### Accuracy:
**86.21%**

### Classification Report:

| Class | Precision | Recall | F1-score |
|--------|----------|--------|----------|
| Hatchback | 0.93 | 0.84 | 0.88 |
| SUV | 0.87 | 0.90 | 0.88 |
| Sedan | 0.81 | 0.82 | 0.82 |

---

## 📷 Screenshots

(Add your screenshots here)

### Gradio Dashboard
![Dashboard](screenshots/dashboard.png)

### Prediction Output
![Prediction](screenshots/output.png)

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/vehicle-classification-system.git
cd vehicle-classification-system
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook Complete_code.ipynb
```

---

## 🌍 Real World Applications

- Smart Traffic Monitoring
- Automated Toll Collection
- Smart Parking Systems
- Vehicle Surveillance
- Urban Planning
- Intelligent Transportation Systems

---

## 🔮 Future Scope

- Add more vehicle categories
- Improve accuracy using hybrid CNN models
- Integrate live CCTV feed
- Cloud deployment
- Mobile application integration

---

## 👨‍💻 Contributors

- Divyanshu Patil
- Ronak Bafna
- Siya Jain

---

## 📄 Project Report

Detailed project report available in repository.

---

## ⭐ If you found this project useful, consider starring the repository!
