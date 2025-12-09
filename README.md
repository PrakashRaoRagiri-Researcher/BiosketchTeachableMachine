# Academic Profile with Animated AI Agent & Teachable Machine Integration

![GitHub Pages](https://img.shields.io/badge/Hosted-GitHub%20Pages-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## Overview
This repository contains Dr. Prakash Rao Ragiri's academic profile webpage integrated with:
- Animated AI chatbot avatar
- Real-time classification feedback using Teachable Machine
- Webcam and microphone interaction

### Features
- Responsive academic profile design
- AI assistant with:
  - Static FAQ responses
  - Voice input (Web Speech API)
  - Speech synthesis
  - Citation graph visualization using Chart.js
- Teachable Machine integration for:
  - Webcam-based image/gesture classification
  - Real-time feedback in chat

## How to Add Your Teachable Machine Model
1. Train your model on [Teachable Machine](https://teachablemachine.withgoogle.com/).
2. Export as TensorFlow.js.
3. Upload model files to your GitHub repository.
4. Replace `YOUR_TEACHABLE_MACHINE_IMAGE_MODEL_URL` in `index.html` with your model path.

## Deployment on GitHub Pages
1. Create a new public repository.
2. Upload `index.html`, `UploadedImage0.jpg`, and model files.
3. Enable GitHub Pages in Settings.
4. Access your site at:
```
https://<username>.github.io/<repository-name>/
```
