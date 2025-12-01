# AI-Based Accident Detection System

## Overview
This project is an **AI-based real-time vehicle detection and accident prediction system**.  
It uses **YOLOv8** and **OpenCV** to detect vehicles in a video stream and can be extended to predict potential accidents, helping reduce emergency response time.

## Features
- Real-time vehicle detection (cars, bikes, trucks, buses)
- Annotates vehicles with bounding boxes
- Can be extended to detect risky behavior and collisions
- Working prototype included in Python

## Tech Stack
- Python
- OpenCV
- Ultralytics YOLOv8
- NumPy

## How to Run
1. **Clone the repository** or download the code:
https://github.com/saraswathipamidi/Accident-Detection-AI

2. **Navigate to the project folder**:
cd Accident-Detection-AI

3. **Install dependencies**:
   pip install -r requirements.txt

   4. **Run the Python script**:
python vehicle_detection.py

5. A window will open showing the **sample video with detected vehicles**.

## Sample Video
- A sample traffic video is included: `sample_video.mp4`

## Future Work
- Accident detection using collision and speed estimation
- Emergency alert system to notify authorities
- Integration with CCTV or dashcam feeds
- Speed estimation and risk scoring

## GitHub Repository
[Accident-Detection-AI](https://github.com/saraswathipamidi/Accident-Detection-AI)

