
# Kidney Tumor Segmentation using Deep Learning

## Overview
This project focuses on developing deep learning models for the segmentation of kidney tumors in CT scans. Utilizing the Kidney Tumor Segmentation Challenge (KiTS) dataset, the project aims to enhance the accuracy of medical image segmentation using advanced neural network architectures.

## Models Developed
- **U-Net:** A convolutional neural network architecture designed specifically for medical image segmentation tasks.
- **V-Net:** An extension of the U-Net architecture, optimized for volumetric data such as CT scans.

## Key Features
- Custom deep learning models leveraging advanced techniques such as convolutional neural networks (CNNs) and fine-tuning.
- Evaluation of model performance using metrics such as accuracy, sensitivity, and specificity.
- Utilization of TensorFlow and Keras libraries for model development, training, and evaluation.

## Dataset
The dataset used in this project is derived from the Kidney Tumor Segmentation Challenge (KiTS). It consists of CT scans focused on kidney tumors, providing a challenging testbed for segmentation models.

## Setup and Installation
1. Clone the repository:
   ```
   git clone https://github.com/your-username/kidney-tumor-segmentation.git
   ```
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Set up a Google Colab environment with GPU support for efficient model training and evaluation.

## Usage
To train and evaluate the models, run the Jupyter notebooks provided in the repository. Ensure that the dataset is correctly loaded and preprocessed before training the models.

## Results
- The developed models achieved an accuracy of 67.90%, with a sensitivity of 65.96% and specificity of 70.59%.
- The results demonstrate the potential of deep learning approaches in improving the accuracy of medical image segmentation tasks.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- This project is based on the Kidney Tumor Segmentation Challenge (KiTS).
- Special thanks to the contributors of the TensorFlow and Keras libraries for providing powerful tools for deep learning research.
