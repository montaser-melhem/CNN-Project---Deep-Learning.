# COVID-19 Detection using Deep Learning

## 📌 Overview

This project presents an intelligent system for detecting COVID-19 from chest X-ray images using Deep Learning techniques. A custom Convolutional Neural Network (CNN) and transfer learning approaches are applied to classify images into COVID-19 and Normal cases.

---

## 📊 Dataset

* Source: Kaggle COVID-19 Radiography Dataset
* Classes:

  * COVID-19
  * Normal
* Size: ~500 images per class

---

## 🧠 Technologies Used

* Python
* TensorFlow / Keras
* NumPy, OpenCV
* Deep Learning (CNN)
* Transfer Learning (ResNet152V2)

---

## 🏗️ Models

The project includes multiple models for comparison:

* **Model 1:** Basic CNN
* **Model 2:** Deeper CNN
* **Model 3:** Optimized CNN (Best Performance)
* **Model 4:** CNN with lung mask preprocessing
* **Transfer Learning:** ResNet152V2

---

## 📈 Results

* Best Accuracy: **96% (Model 3)**
* Transfer Learning Accuracy: **94%**
* Improved generalization and reduced overfitting observed

---

## ⚙️ Installation

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

```bash
python main.py
```

---

## 📁 Project Structure

```
project/
│── data/
│── models/
│── notebooks/
│── main.py
│── requirements.txt
```

---

## 📌 Features

* Automated COVID-19 detection
* Image preprocessing (resizing, normalization)
* Multiple model comparison
* High accuracy classification

---

## 👨‍💻 Authors

* Montaser Melhem
* Montaser Ababneh
* Mahmoud Allobani
