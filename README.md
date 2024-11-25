# Ship Detection in Aerial Images Using YOLOv10

This repository contains the implementation of a ship detection project using the YOLOv10 object detection model. The project leverages aerial image data from the Kaggle dataset [Ships in Aerial Images](https://www.kaggle.com/datasets/siddharthkumarsah/ships-in-aerial-images) and aims to accurately identify and localize ships in complex aerial imagery.

## Project Features

- **Dataset**: The dataset contains annotated aerial images of ships in various maritime settings, including ports and open waters.
- **Model**: YOLOv10, a state-of-the-art object detection model, is used for detecting ships in the dataset.
- **Custom DataLoader**: A custom DataLoader is implemented to provide flexibility and improve preprocessing pipelines.
- **Training Configurations**: Optimized for accuracy using custom configurations and hyperparameter tuning.

---

## Requirements

- Python 3.8+
- Dependencies:
  - PyTorch
  - OpenCV
  - YOLO libraries
  - Pandas, NumPy, Matplotlib
