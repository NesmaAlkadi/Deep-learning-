# Deep-learning-
Deep learning YOLOV5s model

## Model Overview
This project uses a YOLOv5s object detection model trained to recognize 28 classes of sign language gestures across a dataset of 11,000 images with complex backgrounds. The dataset was processed and augmented using Roboflow to ensure high-quality annotations and robust transformations.

# Key Features
## Data Augmentation:
 - Rotation: -17° to +17°
 - Brightness adjustment: -2° to +2°

## Training Details:
 - Image size: 416 x 416
 - Batch size: 16
 - Epochs: 60
 - Data split: 70% training, 10% validation, 10% testing
 - Performance: Achieved 98% accuracy on the test set.
