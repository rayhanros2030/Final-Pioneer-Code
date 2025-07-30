# Gesture Recognition Project

A computer vision project for static and dynamic gesture recognition using machine learning.

## Project Structure

```
.
├── src/           # Source code for all Python scripts
├── data/          # Datasets, models, and media files
├── tests/         # Test scripts
└── README.md      # This file
```

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the pipeline:
```bash
./run_pipeline.sh
```

## Features

- Static gesture recognition
- Dynamic gesture recognition
- Multiple ML models (SVM, LSTM, CNN)
- Real-time video processing

## Models

- Static gestures: SVM with landmark features
- Dynamic gestures: LSTM and 1D CNN temporal models