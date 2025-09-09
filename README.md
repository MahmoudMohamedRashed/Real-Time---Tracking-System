# Real-Time Object Tracking (Graduation Project)

![Language](https://img.shields.io/badge/language-C++-blue.svg)
![CUDA](https://img.shields.io/badge/GPU-CUDA-green)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

![Demo](demo.gif) <!-- Replace with actual GIF file once uploaded -->

## Description
This project is a **real-time object tracking system** developed as a graduation project using **C++**, **CUDA**, and the **Windows API SDK**.  
The system captures live video streams from a USB camera, processes frames in real-time, and tracks objects with high accuracy and performance.

We utilized **Media Foundation** for video capture, the **Win32 API** for creating a lightweight and efficient GUI, and **CUDA** for parallel image processing on the GPU. To further improve performance, a **Lookup Table (LUT)** was implemented for color-space conversions (YUV → RGB, HSI , LUV), significantly reducing the computational overhead.

The system also integrates custom algorithms for trajectory visualization, deform-based analysis, and color-based object detection using the **CIELUV color space**, ensuring robustness under different lighting conditions.

## Features
- 🎯 Real-time object tracking at up to **60 FPS**
- 🎨 Color-space conversions with **Lookup Table optimization** for high speed
- 🧠 Robust object detection using **CIELUV color space**
- 🚀 **CUDA acceleration** for GPU-parallel processing
- ⚡ **Multithreaded pipeline** (capture, processing, rendering)
- 🖼️ Image conversions: YUV → RGB, HSI
- 🪟 **Win32 API GUI** for visualization and rendering
- 📷 Camera access and capture with **Media Foundation**
- 📈 Visualizing trajectories and deform-based analysis in real time
- 
## 🎥 Demo Video
[![Watch the video](https://img.shields.io/badge/Watch%20Video-Google%20Drive-red?logo=google-drive)](https://drive.google.com/file/d/1n8446wEqfd90cXZnX8Mfw-BISiGoeuIU/view?usp=drive_link)

## Installation

### 1. Clone the repository
```bash
git clone https://github.com/MoustafaMahmoud287/RealTime-Tracker.git
cd RealTime-Tracker



