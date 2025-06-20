# AI-Driven-Health-Assessment-for-Flower-Fields


This project presents an AI-driven approach for monitoring floriculture fields using drone-captured images. The system performs flower variety classification and detects underdeveloped or impaired regions in the crop field, helping farmers optimize crop health and productivity.

---

## 🔍 Overview

- 🔎 **Goal:** Automate the detection of flower types and underperforming crop areas using image processing and deep learning.
- 📍 **Study Area:** Khirai, West Bengal, India.
- 🛠️ **Input:** RGB drone images of flower fields.
- 🧠 **Output:** Pixel-wise classification of flower types and impaired zones.

---

## 🧪 Technologies and Algorithms Used

| Component                        | Algorithm / Tool                           |
|----------------------------------|---------------------------------------------|
| Image Segmentation              | K-Means Clustering                          |
| Flower Classification           | Artificial Neural Network (ANN)             |
| Edge Detection                  | Holistically-Nested Edge Detection (HED)    |
| Region Analysis                 | Connected Component Labelling (CCL)         |
| Programming Language            | Python                                      |
| Visualization                   | Matplotlib, OpenCV                          |
| Validation                      | Ground-truth comparison with expert marking |

---


## 📊 Results

- ✔️ Achieved 91.75% training accuracy and 69% validation accuracy in flower classification.
- ✔️ Detected over 90% of impaired crop areas when compared with expert annotations.
- ✔️ Outperformed traditional methods in edge detection (Canny, Sobel).

---

## 🌱 Use Cases

- 🚜 Real-time flower field health monitoring
- 🌾 Precision agriculture and targeted irrigation
- 🛰️ Drone-based agricultural surveying
- 📈 Crop yield optimization

---

## ⚠️ Challenges Faced

- Handling occlusion, lighting variance, and overlapping flower patches.
- Lack of labeled floriculture datasets for training.
- Generalizing across seasonal and regional differences.

---

## 📌 Future Work

- Integration with live drone feeds for real-time analysis.
- Use of multispectral imagery to enhance health diagnostics.
- Expansion to other horticulture crops.
- Incorporation of Explainable AI (XAI) for farmer-facing insights.

---

## 👨‍💻 Authors

- Aryan Vinayak  
- Poulami Karmakar

---

## 📜 License

This project is intended for academic and non-commercial research use. For commercial applications, please contact the author.


