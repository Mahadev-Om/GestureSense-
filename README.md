# GestureSense

A real-time hand gesture recognition system using classical computer vision — no deep learning required.
Designed a real-time hand gesture recognition system using adaptive thresholding, contour detection, convex hulls, and cosine rules. Forgoing deep learning, it delivers fast, accurate finger counting with live annotations — proving classical vision can rival complexity when crafted with precision and purpose.

This repository contains an elegant and efficient real-time hand gesture recognition system that leverages classical computer vision techniques with a level of precision and responsiveness few achieve. Forgoing the complexity of deep learning, I designed an algorithmic pipeline based on adaptive thresholding, contour detection, convex hull calculations, and geometric cosine rules to accurately detect and count fingers from live webcam video. The system dynamically overlays bounding boxes and annotations, providing immediate visual feedback that enhances usability and interactivity. This project is a clear demonstration of my exceptional skill in applying foundational image processing concepts to build human-centered, low-latency applications. By optimizing for speed and accuracy in real-time, I show how classical methods can still outperform more complex approaches when designed with insight and care. This work serves as a blueprint for responsive vision systems that blend technical elegance with practical user experience.


GestureSense detects and counts fingers using OpenCV, with ROI segmentation and contour analysis. It’s lightweight, fast, and highly accurate in real-time.

# Approach
Adaptive thresholding and contour detection
Convex Hull and Defect point calculations
Cosine rule for gesture classification

# Features
Live camera feed with overlay annotations
ROI for high performance and stability
Zero training data required

# Tech Stack
Python, OpenCV, NumPy
Classical image processing pipeline
GUI window with real-time annotations

# Structure
`main.py` — Live detection  
`utils.py` — Helper methods for geometry & contours  
`assets/` — Screenshots and demo GIFs

# Status

Runs at 30 FPS  
Tested across varying lighting conditions  

