# 🧠 Hybrid Acne Detection and Classification

This project is a **course-based project** developed during academic study.
It explores the use of deep learning models for **acne detection and classification**
as part of learning and experimentation in **Computer Vision**.

---

## 📌 Project Overview

The objective of this project is to study and experiment with different deep learning
approaches for acne analysis from facial images.

A **hybrid approach** is explored by comparing:
- Object detection–based methods
- Classification-based methods

The project focuses on understanding model behavior, workflow, and evaluation metrics
rather than building a production-ready system.

---

## 🧠 Approach

Two approaches are implemented and compared:

### 🔹 Detection-Based Approach
- Uses YOLO-based object detection models
- Detects acne regions and predicts their classes

### 🔹 Classification-Based Approach
- Uses image classification techniques
- Predicts acne types directly from images

---

## 📂 Project Structure
```
Hybrid-Acne-Detection-and-Classification/
├── Hybrid_Acne_Detection_and_Classification.ipynb
├── README.md
└── requirements.txt
```


---

## 🛠️ Tools & Libraries

- Python
- PyTorch
- YOLO (Ultralytics)
- OpenCV
- NumPy, Pandas
- Matplotlib
- Jupyter Notebook

---

## 📁 Dataset

The project uses the following datasets for educational purposes:
- **Palvin Dataset (Salpin Dataset)**
- **Jerawat Dataset**

These datasets are used to practice data preprocessing, training, and evaluation.

---

## 📊 Evaluation Metrics

Model performance is evaluated using:
- **mAP@50**
- **mAP@50–95**

These metrics are commonly used for object detection tasks.

---

## ▶️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/simtamet/Hybrid-Acne-Detection-and-Classification.git
cd Hybrid-Acne-Detection-and-Classification
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the notebook
```bash
jupyter notebook Hybrid_Acne_Detection_and_Classification.ipynb
```

## 📝 Notes
- This project is created for learning and academic practice
- The code and results are intended for demonstration purposes
- Model performance may vary depending on dataset and parameters
