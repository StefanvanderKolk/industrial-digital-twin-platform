# Industrial Digital Twin Platform

A modular engineering exploration of industrial machine learning systems for predictive maintenance and visual anomaly detection.

This project focuses on system architecture, reproducibility, and production-aware design rather than benchmark-driven model performance.

---

# Overview

The Industrial Digital Twin Platform simulates two common industrial AI challenges:

1. Predicting Remaining Useful Life (RUL) from multivariate time-series data.
2. Detecting surface defects using visual anomaly detection techniques.

The system is structured as a layered, modular architecture that separates:

- Data engineering
- Model training
- Inference services
- API exposure
- Deployment configuration

The emphasis is on clean system design and reproducible experimentation.

---

# Datasets

### NASA CMAPSS (Turbofan Engine Degradation)

- Multivariate time-series sensor data
- Simulated engine degradation
- Target: Remaining Useful Life (RUL)

Used to explore predictive maintenance modeling.

---

### MVTec AD (Anomaly Detection)

- High-resolution industrial inspection images
- Pixel-level defect annotations
- Multiple product categories

Used to explore visual anomaly detection architectures.

---

# System Architecture

The project follows a layered structure:
