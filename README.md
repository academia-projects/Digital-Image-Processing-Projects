# Digital Image Processing Projects

<div align="center">

Collection of academic digital image processing projects covering  
**classical face detection** and **multi-view 3D reconstruction**.

</div>

---

## 📌 Repository Overview

This repository contains two independent projects:

1. **Viola-Jones Face Detector (Python)**  
   A from-scratch implementation of a Viola-Jones style pipeline using Haar-like features, integral images, AdaBoost, and a cascade classifier.

2. **3D Object Reconstruction (MATLAB)**  
   A simulation-based reconstruction workflow that projects a synthetic 3D chair into multiple camera views and reconstructs it using DLT triangulation.

---

## 🗂️ Repository Organization

```text
Digital-Image-Processing-Projects/
├── README.md
├── 3D_Object_Reconstruction/
│   ├── code.m
│   └── ELL715_A1_2022EE11671.pdf
└── Viola-Jones-Face-Detector/
    ├── train.py
    ├── test.py
    ├── detect_faces.py
    ├── dataset_generator.py
    ├── viola_jones_detector.py
    ├── haar_features.py
    ├── integral_image.py
    ├── adaboost.py
    ├── cascade_classifier.py
    ├── utils.py
    ├── requirements.txt
    ├── faces94/
    └── README.md
```

---

## 🚀 Main Entry Points

### 1) Viola-Jones Face Detector
Run from `Digital-Image-Processing-Projects/Viola-Jones-Face-Detector`.

- **Generate dataset**
  - `python dataset_generator.py`
- **Train model**
  - `python train.py`
- **Evaluate model**
  - `python test.py`
- **Detect faces in a custom image**
  - `python detect_faces.py --image_path <path_to_image>`

### 2) 3D Object Reconstruction
Run from `Digital-Image-Processing-Projects/3D_Object_Reconstruction`.

- **Execute full reconstruction workflow**
  - Open and run `code.m` in MATLAB (or compatible Octave setup)

---

## 🧠 What This Repository Demonstrates

- Classical machine learning for vision (AdaBoost + cascade classifiers)
- Efficient handcrafted feature extraction (integral image + Haar features)
- Sliding-window, multi-scale face detection with NMS post-processing
- Multi-camera geometry simulation and reconstruction quality analysis

---

## 📚 Documentation

- Project-specific setup and usage:
  - `Digital-Image-Processing-Projects/Viola-Jones-Face-Detector/README.md`
  - `Digital-Image-Processing-Projects/Viola-Jones-Face-Detector/INSTRUCTIONS.md`
- Assignment/report material is included inside each project folder.
