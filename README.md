# Transformer-Enhanced YOLO for Underwater Object Detection

This repository contains the source code, models, and instructions for reproducing the results from our paper:

**"Transformer-Enhanced YOLO for Underwater Object Detection and Classification amidst Challenging Lighting Conditions"**,  *
📄 Abstract

Underwater object detection is challenging due to poor lighting and visibility. This work combines a contrast-limited adaptive enhancement method (CLABPHE + sharpening) with an enhanced YOLOv5s model using a Transformer Block and Cross-Convolution module (CC-TBC). Our system improves mAP@0.5, precision, and F1-score over YOLOv5, YOLOv8, and Faster RCNN on the DUO dataset.

---

## 🛠 Requirements

- Python 3.10+
- PyTorch >= 2.0.0
- OpenCV
- Ultralytics (for YOLOv5)
- NumPy, Matplotlib

Install dependencies:
```bash
pip install -r requirements.txt

if you use our code,cite:
@article{prince2025transformer,
  title={Transformer-Enhanced YOLO for Underwater Object Detection and Classification amidst Challenging Lighting Conditions},
  author={Prince, Hena and Binesh, T.},
  
}
