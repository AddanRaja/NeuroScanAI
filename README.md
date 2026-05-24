# NeuroScanAI

AI-powered cross-platform medical imaging platform for Brain Tumor Segmentation and Alzheimer Stage Classification using Deep Learning, Computer Vision, and Full-Stack Development technologies.

---

## Overview

NeuroScanAI is a cross-platform healthcare platform developed for automated Brain Tumor Segmentation and Alzheimer MRI Classification using AI-powered medical imaging pipelines.

The system includes:
- React.js web application
- Flutter mobile application
- FastAPI backend
- PyTorch + MONAI deep learning models
- MySQL database integration

The platform supports secure doctor-patient workflows including MRI upload, AI-assisted analysis, report generation, and patient report delivery.

---

## Key Features

- Brain Tumor Segmentation using SegResNet + MONAI
- Alzheimer Stage Classification using ResNet50 CNN
- MRI slice preview and segmentation overlays
- JWT-based authentication and role-based access control
- Doctor-patient workflow management
- Automated PDF medical report generation
- React web application
- Flutter mobile application
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
