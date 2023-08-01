# Brain-Tumor-Segmentation

## Introduction
Welcome to the Brain Tumor Segmentation project repository! This self-project aims to develop a brain tumor segmentation system capable of identifying and delineating four classes of brain tumors in MRI scans: background, edema, non-enhancing tumor, and enhancing tumor. The project utilizes convolutional neural networks (CNNs), particularly the U-Net model, and makes use of various neuroimaging libraries for visualization and analysis.

## Dataset
The MRI scans dataset used in this project was sourced from the Medical Segmentation Decathlon's Brain Tumor task. The dataset contains annotated brain MRI scans with four distinct classes of brain tumors: background, edema, non-enhancing tumor, and enhancing tumor.

## Data Pre-processing
The MRI scans data went through several pre-processing steps to ensure it is suitable for training the models. The pre-processing included data normalization and resizing to increase the diversity of the training data.


## U-Net Model Training
The U-Net model is a deep learning architecture commonly used for semantic segmentation tasks, particularly in medical image analysis. The U-Net implementation used in this project was developed using PyTorch.The models were trained on the pre-processed MRI scans dataset using an appropriate loss function and optimization techniques.

## Model Evaluation
The trained models were evaluated using multiple metrics, including Accuracy, Precision, Dice coefficient, Specificity, and Sensitivity. These metrics provided a comprehensive understanding of the model's performance.

## Results
The trained U-Net model has shown remarkable performance in accurately identifying and delineating background, edema, non-enhancing tumor, and enhancing tumor regions in brain MRI scans, achieving an impressive accuracy of 98.4% on the test set. This demonstrates its effectiveness and potential as a powerful tool for brain tumor segmentation, aiding medical professionals in diagnosis and treatment planning.
