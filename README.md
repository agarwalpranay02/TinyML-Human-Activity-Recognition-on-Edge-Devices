# Tiny_ML_on_HAR_Dataset
This Project was based on TinyML-Based Lightweight Deep Learning Model for Human Activity Recognition on Edge Devices which also resulted in an conference paper presented at WCAIAA 2026 conference held at NFSU GOA by SCRS


# TinyML-Based Lightweight Deep Learning Model for Human Activity Recognition on Edge Devices 📱⚡

## Overview
This repository contains the implementation of our research paper *“TinyML-Based Lightweight Deep Learning Model for Human Activity Recognition on Edge Devices”*, presented at a conference. The project explores how **compact deep learning architectures** can be optimized for **real-time human activity recognition (HAR)** using smartphone sensor data, while being deployable on **resource-constrained edge devices**.

## Key Highlights
- 📊 **Dataset**: UCI Human Activity Recognition dataset (accelerometer + gyroscope signals).  
- 🧹 **Preprocessing**: Noise filtering, normalization, segmentation into overlapping time windows.  
- 🧠 **Models Implemented**:
  - **NormalCNN1D** – baseline convolutional model.  
  - **MobileNet1D** – lightweight depthwise-separable CNN, best performing (92.77% accuracy).  
  - **CNN + BiLSTM Hybrid** – combines spatial and temporal feature extraction.  
- ⚙️ **Optimization Techniques**:
  - Weight pruning (60% reduction in parameters).  
  - Post-training INT8 quantization (model size reduced to ~1.4 MB).  
  - Knowledge distillation for lightweight student models.  
- 🚀 **Deployment**: Models converted to **TensorFlow Lite** and tested on microcontroller-class hardware (Arduino/ESP32) for real-time inference.  

## Results
- **MobileNet1D** achieved **92.77% accuracy** with balanced precision-recall trade-off.  
- Quantized MobileNet1D retained nearly identical accuracy while reducing size to **under 1.5 MB**.  
- Real-time inference achieved with **latency <100ms** and **power consumption <50mW** on edge devices.  

## Applications
- Health monitoring & fitness tracking.  
- Fall detection & assistive technologies.  
- Gesture control in IoT and wearable devices.  

## Future Scope
- Real-world latency and energy validation on embedded hardware.  
- Exploring transformer-based TinyML architectures.  
- Integration of **federated learning** for personalized HAR.


## Presented at:  
**7th World Conference on Artificial Intelligence: Advances and Applications (WCAIAA 2026)**  
- Organized by: National Forensic Sciences University (NFSU), Goa, India  
- Technically Sponsored by: Soft Computing Research Society (SCRS)  
- 📅 January 30–31, 2026

## 🏅 Conference Presentation Certificate

🎤 Presented this work at **WCAIAA 2026**  

🔗 View Certificate:  
https://drive.google.com/file/d/1ci1EG9D85K83cUhpkDl4lZQx8boihCI-/view?usp=sharing

---

