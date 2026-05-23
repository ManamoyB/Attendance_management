# System Architecture

## Architecture Flow
Camera → Face Detection → Anti-Spoofing → Embedding Extraction → Recognition Model → Database Verification → Attendance Logging

## Components
- OpenCV detection
- TensorFlow anti-spoofing model
- embedding generation
- SVM recognizer
- MySQL persistence layer
- Tkinter GUI
