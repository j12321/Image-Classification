# Image Classification for Geographic Scenes

## Project Overview
This project focuses on classifying geographic scene images into six distinct categories using transfer learning. The model leverages pre-trained models, including ResNet50, ResNet100, EfficientNetB0, and VGG16 to achieve high accuracy in image classification tasks.

## Dataset
* The dataset consists of images labeled into six geographic scene categories.

* Data augmentation techniques were applied to improve generalization.

## Methodology
1. Data Preprocessing:

* Resized images to a uniform input size.

* Applied data augmentation (e.g., flipping, rotation, normalization, etc.).

2. Model Selection & Training:

* Utilized ResNet50, ResNet100, EfficientNetB0, and VGG16 as the base models with pre-trained weights.

* Fine-tuned the last layers to adapt to the geographic scene classification task.

* Implemented early stopping to prevent overfitting.

3. Evaluation Metrics:

* Precision, Recall, AUC, and F1-score were used for performance assessment.


