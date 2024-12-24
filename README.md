# Brain MRI Segmentation using U-Net and TransUnet

## Project Overview
This project focuses on segmenting brain MRI scans using advanced deep learning models, primarily U-Net and TransUnet. The work involves preprocessing MRI images, performing exploratory data analysis (EDA), and implementing models to achieve precise segmentation. The results are visualized for evaluation and interpretation.

## Features
- Image preprocessing with resizing to ensure compatibility with deep learning models.
- Detailed EDA to understand the dataset.
- Implementation of U-Net and fine-tuning of a transformer-based model, TransUnet.
- Visualization of segmentation results.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Exploratory Data Analysis](#exploratory-data-analysis)
4. [Model Implementation](#model-implementation)
5. [Results and Visualization](#results-and-visualization)
6. [Installation](#installation)
7. [Usage](#usage)
8. [Result](#result)


## Introduction
Brain MRI segmentation is a crucial task in medical imaging to identify and delineate regions of interest such as tumors or anatomical structures. This project leverages U-Net and TransUnet architectures to perform segmentation with high accuracy.

## Dataset
The dataset used for this project includes brain MRI scans, sourced from [Kaggle](https://www.kaggle.com). The images are resized to 224x224 for model compatibility. For more details about the dataset, refer to the [dataset link](https://www.kaggle.com/code/arham23/brain-mri-segmentation-eda-and-unet-unet-results/input).


### Preprocessing Steps
1. Resizing images to 224x224.
2. Saving resized images to a dedicated directory for training and validation.

## Exploratory Data Analysis
EDA was performed to:
- Understand the distribution of classes and pixel intensities.
- Visualize sample images and masks.
- Identify potential preprocessing needs.

## Model Implementation
### U-Net
U-Net is a convolutional neural network architecture specifically designed for biomedical image segmentation. Key features:
- Encoder-decoder structure.
- Skip connections to retain spatial information.

### TransUnet
TransUnet integrates transformer modules into the U-Net architecture for enhanced performance. Features:
- Leverages attention mechanisms for capturing global context.
- Fine-tuned for the brain MRI segmentation task.

## Results and Visualization
The segmentation results are visualized to compare the ground truth masks and model predictions. These visualizations help in assessing the model’s performance qualitatively.

## Installation
1. Clone the repository:
   ```bash
   [https://github.com/Vinay87950/Deep_vision.git]
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt

## Usage
1. Dataset Preparation
2. Training the Model
3. Evaluating the Model
4. Visualizing Results
5. Hyperparameter Tuning

## Result 

<img src="https://github.com/Vinay87950/Deep_vision/blob/main/latex/train_loss.png" width="600"/>
<img src="https://github.com/Vinay87950/Deep_vision/blob/main/latex/val_loss.png" width="600"/>


