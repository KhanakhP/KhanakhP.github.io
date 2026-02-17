---
title: "Robotics and Artificial Intelligence"
collection: teaching
type: "Intern"
permalink: /experience/iit-mandi
venue: "IIT Mandi, Drone Lab"
date: 2025-11-10
location: "Mandi, India"
---

Contributing to advanced robotics and AI research at one of India's premier technical institutes, focusing on transformer-based systems, computer vision applications, and real-time deployment for autonomous systems.

#### Key Responsibilities & Achievements:

**Transformer-Based Language Systems**
- Architected and implemented a GPT-style transformer model from scratch in PyTorch, incorporating token embeddings, positional encodings, multi-head self-attention mechanisms, feed-forward networks, residual connections, and layer normalization
- Validated model correctness through successful loading of pretrained weights and inference execution for language modeling tasks
- Fine-tuned GPT-2 for SMS classification by replacing the language modeling head with a task-specific classification layer and selectively updating final transformer blocks
- Reconfigured tokenization pipelines, attention masking, and training procedures using Hugging Face Transformers library

**Computer Vision & Real-Time Systems**
- Developed and compared object tracking algorithms using CamShift and MeanShift with HSV color histograms for robust target following in video streams
- Implemented ArUco marker detection for precise position estimation in robotics applications
- Applied Farneback optical flow algorithms to measure camera displacement between consecutive frames
- Designed failure detection mechanisms based on area collapse and drift thresholds with automatic re-initialization capabilities

**CNN-Based Terrain Classification for Robotics**
- Designed and trained convolutional neural networks to identify terrain types for autonomous robot navigation
- Evaluated multiple model architectures under strict real-time performance constraints
- Optimized models for deployment on edge hardware, achieving consistent 30+ FPS inference rates
- Converted final production models to ONNX format for seamless integration with robotic systems

#### Technical Environment:
PyTorch, TensorFlow, Hugging Face Transformers, OpenCV, NumPy, Pandas, ONNX, QGroundControl

#### Skills Developed:
Deep Learning Architecture Design, Transfer Learning, Real-Time Computer Vision, Model Optimization, Edge Deployment, Robotics Integration

<nav style="margin-bottom: 30px; padding: 10px 0; ">
  <a href="/" style="color: #52adc8; text-decoration: none;">Home</a> 
  <span style="color: #999;"> / </span>
  <a href="/experience/" style="color: #52adc8; text-decoration: none;">Experience</a>
  <span style="color: #999;"> / </span>
  <span style="color: #666;">{{ page.title }}</span>
</nav>