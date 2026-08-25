
# 🔬 Pancreatic Cancer Detection
### Deep Learning Pipeline for Medical Imaging Classification

<p align="center">
<img src="https://img.shields.io/badge/Python-3.9+-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/TensorFlow-Deep%20Learning-FF6F00?style=for-the-badge&logo=tensorflow">
<img src="https://img.shields.io/badge/Computer_Vision-OpenCV-5C3EE8?style=for-the-badge&logo=opencv">
<img src="https://img.shields.io/badge/Model-CNN%20Ensemble-white?style=for-the-badge">
<img src="https://img.shields.io/badge/Accuracy-Up%20to%20100%25-brightgreen?style=for-the-badge">
</p>

---

## 🌟 Overview

Pancreatic cancer is one of the most aggressive forms of cancer, making early and accurate detection critical for patient outcomes. This project implements a cutting-edge **Deep Learning framework** to classify medical imaging data into cancerous and non-cancerous categories. By benchmarking multiple **Convolutional Neural Network (CNN)** architectures, this tool provides a robust automated diagnostic assistant for medical professionals.



---

## 🎯 Key Features

* ✅ **Extensive Model Benchmarking:** Comparative analysis across 6 high-performance architectures including ResNet, VGG, and EfficientNet variants.
* ✅ **Advanced Image Preprocessing:** Robust pipeline featuring normalization, resizing, and **Data Augmentation** to prevent overfitting.
* ✅ **In-depth Evaluation:** Detailed performance visualization through confusion matrices and ROC-AUC curves.
* ✅ **Comprehensive Metrics:** Tracking Precision, Recall, F1-Score, and overall Accuracy for clinical reliability.

---

## 🧠 Tech Stack

| Category | Tools |
| :--- | :--- |
| **Language** | Python 3.9+ |
| **Deep Learning** | TensorFlow, Keras |
| **Computer Vision** | OpenCV |
| **Data Science** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |

---

## 📁 Project Structure

```bash
Pancreatic-cancer-detection/
├── confusion_matrices/       # Performance plots for each architecture
│   ├── EfficientDense_cm.png
│   ├── EfficientV3_cm.png
│   └── ... 
├── major_project.ipynb       # Core implementation & training notebook
├── pancreatic_cancer.xlsx    # Tabular metadata & dataset references
├── Report.docx               # Academic project documentation
├── requirements.txt          # Python environment dependencies
└── README.md                 # Project overview

```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone [https://github.com/G-Narendra/Pancreatic-cancer-detection.git](https://github.com/G-Narendra/Pancreatic-cancer-detection.git)
cd Pancreatic-cancer-detection

```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt

```

### 3️⃣ Run the Notebook

```bash
jupyter notebook major_project.ipynb

```

---

## 📊 Performance Comparison

### **Model Metrics (%)**

| Model | Accuracy | Precision | Recall | F1-Score |
| --- | --- | --- | --- | --- |
| **EfficientDense** | **100.00** | **100.00** | **100.00** | **100.00** |
| **EfficientV3** | **100.00** | **100.00** | **100.00** | **100.00** |
| InceptionDense | 99.75 | 99.47 | 100.00 | 99.73 |
| EfficientVGG | 99.75 | 99.47 | 100.00 | 99.73 |
| VGG16V2 | 72.98 | 100.00 | 42.78 | 59.93 |
| ResNetV2 | 65.40 | 57.72 | 100.00 | 73.19 |

### **Analysis:**

The **EfficientNet-based variants (EfficientDense and EfficientV3)** significantly outperformed traditional architectures like ResNet and VGG, achieving perfect scores on the test set. This highlights the effectiveness of compound scaling in feature extraction for complex medical textures.

---

## Engineering Decisions & Challenges Solved

| Challenge | Decision | Why |
|---|---|---|
| Limited labeled medical images for training | Transfer learning with pretrained CNNs (VGG16, ResNet50, InceptionV3) fine-tuned on medical data | Pretrained features generalize well; fine-tuning adapts them to medical imaging domain without needing millions of labeled images |
| Class imbalance (fewer cancer-positive cases) | Stratified splitting and class-weighted loss function | Ensures the model doesn't just predict the majority class — critical for medical diagnosis where missing positives has severe consequences |
| Comparing multiple architectures fairly | Identical preprocessing, split ratios, and evaluation metrics across all models | Fair comparison requires controlled variables — only the model architecture differs between experiments |
| Model interpretability for medical use | Accuracy, precision, recall, F1-score, and confusion matrix reported per model | A single accuracy number hides the cost of false negatives in cancer detection — full metrics expose the trade-offs |

## 👨‍💻 Author

**Narendra (G‑Narendra)** AI | ML | Python | Full Stack | GenAI Enthusiast

📧 [Email Me](mailto:narendragandikota2540@gmail.com) | 💼 [LinkedIn](https://linkedin.com/in/g-narendra/) | 👨‍💻 [GitHub](https://github.com/G-Narendra)

---

<p align="center">⭐ If you find this project useful, feel free to give it a star! 🚀</p>

