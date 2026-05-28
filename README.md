# Real-Time Human Identification & Emotion Analysis

> Python + OpenCV computer vision system for real-time gender 
> classification, height estimation, and emotion detection. 
> Proof-of-concept for retail footfall analytics.

---

## Business Problem

Retailers and venue operators lack real-time insight into customer 
demographics and emotional responses on the shop floor. Manual 
observation is slow, inconsistent, and unscalable. This project 
builds a computer vision proof-of-concept that automatically 
captures customer demographic data and sentiment signals in 
real time — enabling data-driven decisions in retail analytics, 
customer experience, and store layout optimisation.

---

## Solution

Built a real-time video analysis system using Python and OpenCV 
that detects and classifies:
- **Gender** — binary classification from facial features
- **Height estimation** — using bounding box proportions and 
  reference calibration
- **Emotion detection** — classifying facial expressions into 
  core emotional states (happy, neutral, surprised, sad, angry)

---

## Use Cases

- Retail footfall demographic analysis
- In-store customer sentiment monitoring
- Queue management and wait-time emotional impact analysis
- Event and venue audience analytics
- Proof-of-concept for smart retail and digital signage targeting

---

## Methods

**1. Face Detection**
- Haar Cascade / DNN-based face detector (OpenCV)
- Real-time bounding box identification

**2. Gender Classification**
- Pre-trained deep learning model for binary gender prediction
- Confidence score output

**3. Emotion Detection**
- Facial Action Coding System (FACS)-inspired feature extraction
- Classification into 7 core emotional states
- Frame-by-frame real-time prediction

**4. Height Estimation**
- Reference object calibration approach
- Bounding box pixel-to-real-world mapping

---

## Tools & Technologies

| Category | Tools |
|---|---|
| Language | Python |
| Computer Vision | OpenCV |
| Deep Learning | TensorFlow / Keras |
| Data Processing | NumPy, Pandas |
| Visualisation | Matplotlib |
| Environment | Jupyter Notebook |

---

## Ethical Note

This project is a technical proof-of-concept built for academic 
and analytical research purposes. Any real-world deployment would 
require full compliance with GDPR, the EU AI Act, and applicable 
data protection regulations, including explicit user consent and 
transparent data handling policies.

---

## Author

**Basant Kumar** — Business Analyst | Data & AI Analytics  
MSc Business Analytics, Maynooth University  
[LinkedIn](https://linkedin.com/in/basantsingh-) | 
[GitHub](https://github.com/Basantsingh607)
