# Face Mask Detection with YOLO

This project provides a Jupyter notebook to train, evaluate, and run real-time inference for a face mask detection model using the Ultralytics YOLO API.

## Contents

- `notebooks/face-mask-detection-yolo.ipynb`: End-to-end notebook
- `data/`: Placeholder for datasets (created by the notebook)
- `runs/`: Training runs and exported models (created by the notebook)

## Requirements

- Python 3.8+
- GPU (CUDA) recommended for training and real-time inference; CPU is supported

Required packages (the notebook installs them automatically if missing):

- ultralytics
- opencv-python
- matplotlib, seaborn, numpy, pandas
- roboflow (optional, for dataset import)

## How to use

1. Open the notebook at `notebooks/face-mask-detection-yolo.ipynb`.
2. Choose one of the dataset options (Roboflow, Kaggle, or local in YOLO format) in the Data section.
3. Run the training cells; best weights are saved under `Computer Vision/FaceMaskDetection_YOLO/runs/train/mask-yolo/weights/best.pt`.
4. Run the evaluation and inference cells to test on images, videos, or webcam.

## Notes

- The notebook includes a minimal local-dataset example and optional Roboflow import for convenience.
- Real-time webcam inference uses OpenCV; ensure your camera works and you have permission.
- On Windows, you may need to allow camera access via Privacy settings.
