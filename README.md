# Helmet Compliance Detector

> Real-time helmet detection for workplace safety compliance
> using YOLOv8-Nano (YOLOv8n)

## Overview
A lightweight helmet compliance detection system built for 
workplace safety monitoring. Detects whether workers are wearing 
helmets or not in real-time, designed to run efficiently on 
edge devices without requiring high-end hardware.

## Results

| Metric | Score |
|---|---|
| mAP@0.5 | 97.3% |
| mAP@0.5:0.95 | 68.8% |
| Precision | 94.2% |
| Recall | 93.5% |

## Classes
- `helmet` — worker wearing helmet ✅
- `no_helmet` — worker without helmet ❌

## Dataset
See [dataset/README.md](dataset/README.md)

## Architecture
YOLOv8-Nano (YOLOv8n) — optimized for speed and edge deployment 
without significant accuracy tradeoff.

## Tech Stack
- Python 3.8+
- PyTorch 2.0+
- Ultralytics YOLOv8
- Streamlit (deployment — in progress)

## Model Weights
Due to file size, weights are hosted on Google Drive.
- [Download best.pt]([your_drive_link_here](https://drive.google.com/drive/folders/1J-gCaDv5NzWeosneMhx03gsY4XKq6jRG?usp=drive_link))
or See [models/README.md](models/README.md)
## Status
🚧 Streamlit deployment in progress
