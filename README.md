# 👁️ AI-Based Intelligent Healthcare System

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![Deep Learning](https://img.shields.io/badge/Deep-Learning-YOLOv8-green)
![Healthcare](https://img.shields.io/badge/Healthcare-AI-red)
![License](https://img.shields.io/badge/License-MIT-orange)

An **AI-powered Intelligent Healthcare System** for automated eye disease detection and classification using lightweight deep learning and explainable artificial intelligence.

This repository provides:

✅ Source Code
✅ Custom Annotated Dataset
✅ Trained Models
✅ Experimental Results
✅ Explainable AI Visualizations
✅ Research Manuscript

The proposed framework is designed for:

* Telemedicine
* Smart Healthcare
* Mobile Healthcare
* Edge AI Applications
* Resource-Constrained Clinical Settings

---

# 🌟 Highlights

* Lightweight YOLOv8-based architecture
* Real-time disease detection
* Expert-annotated clinical eye image dataset
* Four-class eye disease classification
* Explainable AI using Eigen-CAM
* Compact and efficient model
* Suitable for mobile and edge deployment
* Designed for resource-limited healthcare environments

---

# 🏥 Applications

* Automated Eye Disease Screening
* Telemedicine Platforms
* Rural Healthcare Centers
* Mobile Diagnostic Applications
* Smart Hospitals
* Clinical Decision Support Systems

---

# 📂 Repository Structure

```text
AI-Based-Intelligent-Healthcare-System/

├── AI_Based_Intelligent_Healthcare_System.ipynb

├── dataset/
│   └── conjunctivitis_dataset.zip

├── models/
│   └── yolov8_best.pt

├── figures/
│   ├── data_collection_and_sample_images.png
│   ├── ai_healthcare_detection_result.png
│   ├── confusion_matrix.png
│   ├── eigen_cam_detection_result.png
│   └── system_architecture.png

├── paper/
│   └── AI_Healthcare_Research_Manuscript.pdf

├── requirements.txt

├── LICENSE

└── README.md
```

---

# 📊 Dataset

The custom-curated clinical dataset contains:

| Property     |                   Value |
| ------------ | ----------------------: |
| Total Images |                   3,469 |
| Resolution   |               640 × 640 |
| Annotation   | Expert Ophthalmologists |
| Image Type   |     Clinical Eye Images |
| Classes      |                       4 |

### Classes

| Class | Description        |
| ----- | ------------------ |
| BPE   | Bacterial Pink Eye |
| APE   | Allergic Pink Eye  |
| VPE   | Viral Pink Eye     |
| NE    | Normal Eye         |

---

# 🤖 Model

The proposed framework employs **YOLOv8** as the backbone architecture due to its excellent balance between:

* Accuracy
* Lightweight Design
* Computational Efficiency
* Real-Time Performance

### Performance Features

* High Detection Accuracy
* Lightweight Model Architecture
* Real-Time Inference
* Edge Device Compatibility
* Explainable Predictions
* Robust Clinical Performance

---

# 🔍 Explainable AI

To improve transparency and clinical trust, the system integrates:

* Eigen-CAM
* Saliency Visualization
* Heatmap Analysis

These methods identify important image regions contributing to the final prediction and support clinically interpretable diagnosis.

---

# 🖼 Figures

### Data Collection and Sample Images

```text
figures/data_collection_and_sample_images.png
```

Clinical image acquisition and representative samples used for AI model development.

---

### AI Detection Results

```text
figures/ai_healthcare_detection_result.png
```

Real-time prediction and disease localization using AI.

---

### Explainability Results

```text
figures/eigen_cam_detection_result.png
```

Eigen-CAM visualization highlighting important image regions responsible for model predictions.

---

# 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/AI-Based-Intelligent-Healthcare-System.git

cd AI-Based-Intelligent-Healthcare-System
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# ▶ Usage

Open the notebook:

```bash
AI_Based_Intelligent_Healthcare_System.ipynb
```

or run:

```bash
python train.py
```

For prediction:

```bash
python predict.py
```

---

# 📄 Research Status

This repository contains the implementation, dataset, and experimental results of an **AI-Based Intelligent Healthcare System** for automated eye disease detection and classification.

The associated research manuscript is currently **under peer review** in an international journal.

This repository is maintained to promote:

* Open and Reproducible Research
* AI-Driven Healthcare Innovation
* Explainable Artificial Intelligence (XAI)
* Real-Time Clinical Decision Support
* Collaboration Among Researchers and Healthcare Professionals

Updates regarding the manuscript and related publications will be added upon acceptance.

---

# 👨‍🔬 Authors

### Saima Kanwal †

Engineering Research Centre of Optical Instrument and Systems
University of Shanghai for Science and Technology, Shanghai, China

---

### Muhammad Abdullah †

Faculty of Computing
The Islamia University of Bahawalpur, Pakistan

---

### Sahil Kumar

Department of Computer Science
SZABIST University Larkana Campus, Pakistan

---

### Santosh Kumar

Bolan Medical Complex Hospital
Quetta, Pakistan

---

### Dawei Zhang

University of Shanghai for Science and Technology
Shanghai, China

---

### Dileep Kumar *

Faculty of Engineering
The Islamia University of Bahawalpur, Pakistan

---

***** Corresponding Author

**†** Equal Contribution

---

# ⭐ Support

If you find this repository useful:

⭐ Star this repository

🍴 Fork this repository

🤝 Contribute to the project

📢 Share with the research community

Together, we can advance **AI-driven Intelligent Healthcare** for accessible, transparent, and reliable medical diagnosis.
