# AI Passport Photo Generator

## Overview
This project is a full-stack web application that automates passport photo creation using AI-based background removal. It allows users to upload an image and generate a clean, compliant passport-style photo in real time.

## Features
- Automated background removal using deep learning
- Human segmentation with high accuracy
- Real-time image processing
- Simple and user-friendly interface
- Free and accessible tool for official photo generation

## Tech Stack
- Python  
- Flask  
- PyTorch  
- HTML/CSS  

## Model Details
- Implemented a lightweight U-Net architecture  
- Used MobileNetV3 as the backbone for efficient feature extraction  
- Trained on a custom dataset of 250+ annotated images  
- Optimized for fast and accurate human segmentation
  
## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/aadrikanandastudent-pixel/ai-passport-photo-app.git

2. Navigate to the project folder
   </> Bash
       cd ai-passport-photo-app

3. Run the flask app 
   python app.py
