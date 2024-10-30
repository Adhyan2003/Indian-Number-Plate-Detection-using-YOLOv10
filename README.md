**Indian License Plate Detection using YOLOv10**
This project focuses on detecting Indian license plates from images using the YOLOv10 model. This repository includes code for setting up, training, and evaluating a YOLOv10-based object detection model on a dataset of Indian license plates. Below are the key features and steps involved in the project.

**Project Structure**
1. Dependencies: Installs YOLOv10, ultralytics, and additional tools like Kaggle API for dataset access.
2. Dataset Preparation: Downloads and organizes the "Indian License Plate" dataset from Kaggle. Paths are set for training and testing images, and label verification ensures each image has an associated annotation.
3. Model Training: The YOLOv10 model is trained with parameters tuned for optimal detection accuracy, and the best model weights are saved for evaluation.
4. Evaluation and Metrics:
   - Generates loss curves and precision-recall plots to analyze training progress.
   - Calculates model accuracy on the test set.
   - Evaluates confidence scores, detection counts, and Intersection over Union (IoU) distributions.
5. Results Visualization: Provides insights into the model’s performance with visual plots of accuracy, IoU, detection counts, and confidence distribution.
6. Performance Metrics: Displays mAP, precision, and recall metrics for license plate detection.
   
**Requirements**
1. YOLOv10 library
2. Kaggle API access (for downloading datasets)
3. Python packages: albumentations, ultralytics, matplotlib, pandas, etc.
