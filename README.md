# Automatic Number Plate Detection — YOLOv8

Real-time vehicle number plate detection from CCTV 
footage using YOLOv8 and HuggingFace models.

## Tech Stack
- **Model:** YOLOv8 (You Only Look Once)
- **Platform:** HuggingFace
- **Language:** Python
- **Libraries:** OpenCV, NumPy, Ultralytics

## Features
- Real-time detection from CCTV video feed
- High-accuracy bounding box detection
- Works across different lighting conditions
- Fast inference — single-pass detection architecture

## How It Works
1. Video feed ingested from CCTV source
2. YOLOv8 runs single-pass object detection
3. Number plate region identified and cropped
4. OCR extracts plate text in real-time
5. Output logged with timestamp and plate number

## Reference
Built following YOLOv8 implementation for 
real-time number plate detection.

## Built By
Shreya Bangale | [Portfolio](https://buildsbyshreya.framer.ai)
