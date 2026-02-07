# objectdetectionCNN
Developed a real-time object detection system using YOLOv10 for high-speed and accurate detection. Integrated ByteTrack to enable stable multi-object tracking and reduce bounding box jitter. Supports image, video, and webcam inputs with smooth, real-time performance on standard hardware.
Object Detection System
Project Overview

This project implements a real-time object detection system using computer vision and deep learning techniques. The system automatically detects and localizes multiple objects in images, videos, and live webcam streams, reducing the need for manual monitoring and visual inspection.

Key Features

Real-time object detection from images, videos, and live webcam feed

Accurate bounding boxes, class labels, and confidence scores

Uses a CNN-based pre-trained object detection model

Optimized for better frame rate and detection stability

Handles edge cases such as invalid frames and varying lighting conditions

Technologies Used

Programming Language: Python

Computer Vision: OpenCV

Deep Learning: CNN-based pre-trained object detection model

Development Tool: VS Code

System Workflow

Captures input frames using OpenCV

Preprocesses frames (resizing, normalization, blob conversion)

Performs object detection using a CNN-based model

Applies Non-Maximum Suppression (NMS) to remove duplicate detections

Displays results with bounding boxes and confidence scores in real time

Applications

Surveillance systems

Smart automation

Safety monitoring

AI-based vision systems

Future Enhancements

Training with custom datasets for domain-specific detection

Improving performance under low-light conditions

Deployment on edge devices like Raspberry Pi and Jetson Nano

Integration with IoT and real-time monitoring systems
