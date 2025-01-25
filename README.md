# Opt-SAR DINO Model

Welcome to the Opt-SAR DINO repository! This project is dedicated to object detection on optical and SAR images, specifically designed for small-scale objects. The repository includes:

## Datasets
1. **Pleiades Aircraft Dataset**: For object detection on optical images (aircraft detection).
2. **SSDD Dataset**: For object detection on radar images (ship detection).

## Structure
```
root/
│
├── Pleiades Aircraft Dataset/
│   ├── Opt-SAR-DINO.ipynb
│   ├── Deformable DETR.ipynb
│   ├── DETR.ipynb
│   ├── Faster R-CNN.ipynb
│   ├── YOLOV10.ipynb
│   └── RetinaNet.ipynb
│
├── SSDD Dataset/
│   ├── OPT-SAR-DINO.ipynb
│   ├── Deformable DETR.ipynb
│   ├── DETR.ipynb
│   ├── Faster R-CNN.ipynb
│   ├── YOLOV10.ipynb
│   └── RetinaNet.ipynb
│
└── README.txt
```

## Execution of Notebooks
All notebooks are designed to be executed in a Google Colab environment. We strongly recommend using a GPU for training and evaluation, preferably **NVIDIA A100** for optimal performance.

## Testing and Visualization
Each notebook includes:
- **Visualization** of predictions.
- Calculation of evaluation metrics:
  - Precision
  - Recall
  - F1-Score
  - mAP@50
  - mAP@75
  - mAP@[0.5:0.95]

Feel free to explore and contribute!
