Brain MRI Segmentation using U-Net and TransUnet

Project Overview

This project focuses on segmenting brain MRI scans using advanced deep learning models, primarily U-Net and TransUnet. The work involves preprocessing MRI images, performing exploratory data analysis (EDA), and implementing models to achieve precise segmentation. The results are visualized for evaluation and interpretation.

Features

Image preprocessing with resizing to ensure compatibility with deep learning models.

Detailed EDA to understand the dataset.

Implementation of U-Net and fine-tuning of a transformer-based model, TransUnet.

Visualization of segmentation results.

Table of Contents

Introduction

Dataset

Exploratory Data Analysis

Model Implementation

Results and Visualization

Installation

Usage

Contributing

License

Introduction

Brain MRI segmentation is a crucial task in medical imaging to identify and delineate regions of interest such as tumors or anatomical structures. This project leverages U-Net and TransUnet architectures to perform segmentation with high accuracy.

Dataset

The dataset used for this project includes brain MRI scans, sourced from Kaggle. The images are resized to 224x224 for model compatibility. For more details about the dataset, refer to the dataset link.

Preprocessing Steps

Resizing images to 224x224.

Saving resized images to a dedicated directory for training and validation.

Exploratory Data Analysis

EDA was performed to:

Understand the distribution of classes and pixel intensities.

Visualize sample images and masks.

Identify potential preprocessing needs.

Model Implementation

U-Net

U-Net is a convolutional neural network architecture specifically designed for biomedical image segmentation. Key features:

Encoder-decoder structure.

Skip connections to retain spatial information.

TransUnet

TransUnet integrates transformer modules into the U-Net architecture for enhanced performance. Features:

Leverages attention mechanisms for capturing global context.

Fine-tuned for the brain MRI segmentation task.

Results and Visualization

The segmentation results are visualized to compare the ground truth masks and model predictions. These visualizations help in assessing the model’s performance qualitatively.

Installation

Clone the repository:

git clone https://github.com/yourusername/your-repo.git

Navigate to the project directory:

cd your-repo

Install required dependencies:

pip install -r requirements.txt

Usage

Preprocess the dataset:

Ensure images are resized and saved in the appropriate directory.

Train the model:

python train.py

Visualize results:

python visualize.py

Contributing

Contributions are welcome! Please follow these steps:

Fork the repository.

Create a new branch for your feature/bug fix.

Submit a pull request with a clear description of your changes.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments

Philipp Götz for assistance with GitLab integration.

Kaggle community for providing the dataset and initial implementations.

Feel free to reach out with any questions or suggestions for improvement.

