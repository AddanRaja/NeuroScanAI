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

## Web Application Screenshots

### Login Page
![Login Page](Web%20SS/login-page.png)

### Patient Dashboard — Tumor Module
![Patient Dashboard Tumor](Web%20SS/patient-dashboard-tumor-module.png)

### Patient Dashboard — Alzheimer Module
![Patient Dashboard Alzheimer](Web%20SS/patient-dashboard-alzheimer-module.png)

### Doctor Dashboard
![Doctor Dashboard](Web%20SS/doctor-dashboard.png)

### MRI Upload Workflow
![MRI Upload](Web%20SS/mri-upload.png)

### Brain Tumor Segmentation Result
![Tumor Segmentation](Web%20SS/tumor-segmentation-result.png)

### Alzheimer Classification Result
![Alzheimer Result](Web%20SS/alzheimer-classification-result.png)

### Generated Medical Report
![Medical Report](Web%20SS/medical-report.png)

---

## Mobile Application Screenshots

### Home Page
![Home Page](Mobile%20SS/Home%20Page/mobile-home.jpg)

### Patient Module
![Patient Module](Mobile%20SS/Patient/patient-dashboard.jpg)

### Doctor Module
![Doctor Module](Mobile%20SS/Doctor/doctor-dashboard.jpg)

### Admin Module
![Admin Module](Mobile%20SS/Admin/admin-dashboard.jpg)

### Contact Us
![Contact Us](Mobile%20SS/Contact%20Us/contact-page.jpg)

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
