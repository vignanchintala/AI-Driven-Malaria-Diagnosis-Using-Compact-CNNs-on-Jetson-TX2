AI-Driven Malaria Diagnosis Using Compact CNNs on Jetson TX2

An end-to-end lightweight deep learning system for automatic malaria parasite detection from microscopic blood smear images, optimized for real-time inference on NVIDIA Jetson TX2.
This project focuses on deploying compact CNN architectures to achieve high accuracy while maintaining low computational cost, enabling on-device, offline diagnosis in resource-limited environments.

🚀 Project Overview

Malaria remains a major global health challenge, especially in regions with limited access to laboratory experts. This project aims to automate the diagnosis process by:

Classifying blood smear images as Parasitized or Uninfected

Using compact deep learning models (MiniCNN, MobileNetV2-lite, EfficientNet-Tiny)

Deploying the optimized model on Jetson TX2 for real-time performance

Ensuring low latency, low power consumption, and field applicability

🧠 Key Features

Compact CNN Architectures: Designed for efficiency without compromising accuracy

Jetson TX2 Deployment: ONNX + TensorRT optimization for fast inference

Dataset Preprocessing: Augmentation, normalization, and balanced sampling

Performance Metrics: Accuracy, F1-Score, ROC, inference time, FPS

Real-Time GUI: Optional Python/Tkinter interface to upload and classify images

Scalable Pipeline: Can be extended to other cell-image classification tasks
