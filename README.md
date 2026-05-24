# NeuroScanAI

AI-powered cross-platform medical imaging platform for Brain Tumor Segmentation and Alzheimer Stage Classification using Deep Learning, Computer Vision, and Full-Stack Development technologies.

---

## Overview

NeuroScanAI is a cross-platform healthcare platform developed for automated Brain Tumor Segmentation and Alzheimer MRI Classification using AI-powered medical imaging pipelines.

The platform includes:
- React.js web application
- Flutter mobile application
- FastAPI backend
- PyTorch + MONAI deep learning models
- MySQL database integration

The system supports secure doctor-patient workflows including MRI upload, AI-assisted analysis, report generation, and patient report delivery.

---

## Key Features

- Brain Tumor Segmentation using SegResNet + MONAI
- Alzheimer Stage Classification using ResNet50 CNN
- MRI slice preview and segmentation overlays
- Role-based authentication and access control
- Doctor-patient workflow management
- Automated PDF medical report generation
- Cross-platform web and mobile applications
- AI-powered MRI preprocessing and inference pipelines

---

## Technology Stack

### Frontend & Mobile
- React.js
- Flutter
- Tailwind CSS
- Bootstrap

### Backend
- FastAPI
- MySQL
- SQLAlchemy

### AI / Machine Learning
- PyTorch
- MONAI
- OpenCV
- NumPy
- Matplotlib

---

## Project Architecture

```text
React Web App        Flutter Mobile App
        │                    │
        └────── API Requests ──────┘
                     │
               FastAPI Backend
                     │
       ┌─────────────┴─────────────┐
       │                           │
 Brain Tumor Pipeline      Alzheimer Pipeline
 (SegResNet + MONAI)       (ResNet50 CNN)
       │                           │
       └────────── MRI Analysis ───┘
                     │
                 MySQL Database
```

---

## Brain Tumor Segmentation Workflow

1. Upload multimodal MRI scans (T1C, T1N, T2F, T2W)
2. MRI preprocessing and normalization
3. SegResNet performs voxel-level segmentation
4. Segmentation overlays generated
5. Doctor reviews AI-assisted analysis
6. PDF report generated and delivered to patient

---

## Future Improvements

- Cloud deployment
- Real-time MRI streaming
- Advanced explainable AI visualization
- Multi-language support
- PACS/DICOM integration
- Hospital management integration

---

## Author

Muhammad Addan Raja
