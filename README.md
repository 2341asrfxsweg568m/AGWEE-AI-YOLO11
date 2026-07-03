# AGWEE.AI — YOLO11 Smart Agriculture Project

AGWEE.AI is a PyTorch-based deep learning project developed to identify
crop and weed plant seedlings using YOLO11 image classification.

## Project Objective

The objective of this project is to develop an artificial intelligence
model that analyzes a plant image and predicts its plant species.

The predicted species is then evaluated as one of two agricultural groups:

- Crop
- Weed

The system can form the visual intelligence component of:

- Agricultural robots
- Mobile farming applications
- Greenhouse monitoring systems
- Drone-based field monitoring systems
- Decision support systems

## Technologies

- Python
- PyTorch
- Ultralytics YOLO11
- Google Colab
- Torchvision
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Dataset

This project uses the V2 Plant Seedlings Dataset.

The dataset contains images from 12 plant seedling species and different
growth stages.

The dataset itself is not stored in this repository.

## Model

The initial model is:

YOLO11n Classification

Pretrained weights are fine-tuned using the Plant Seedlings Dataset.

## Evaluation Metrics

The model will be evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
- Top-1 accuracy
- Top-5 accuracy

## Development Environment

The model is trained in Google Colab using GPU acceleration.

## Author

Ali İsgandarov  
Computer Engineering  
Student Number: 20222013339
