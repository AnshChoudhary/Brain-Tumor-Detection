# Brain Tumor Detection Model with CNN using TensorFlow

This repository contains a deep learning project for detecting brain tumors using Convolutional Neural Networks (CNNs) implemented in TensorFlow. The model is trained on a dataset of brain MRI images and can classify whether an input MRI scan contains a tumor or not.

## Dataset
This dataset contains 7023 images of human brain MRI images which are classified into 4 classes: glioma - meningioma - no tumor and pituitary. The dataset used for training and testing the model consists of brain MRI images. It includes both images with tumors and images without tumors. Each folder has more four subfolders. These folders have MRIs of respective tumor classes.

## Requirements
- Python
- TensorFlow
- NumPy
- Matplotlib
- Other dependencies listed in `requirements.txt`

## Installation
1. Clone the repository:
   ```bash
     git clone https://github.com/AnshChoudhary/Brain-Tumor-Detection.git
2. Install all the dependencies
3. Run the model on Jupyter Notebooks or Google Collab

## Usage
1. **Data Preparation**: Obtain a dataset of brain MRI images. Organize the dataset into two folders: one containing images with tumors and another containing images without tumors.

2. **Data Preprocessing**: Preprocess the images, ensuring they are all in the same format, size, and resolution. Normalize the pixel values to a range suitable for training neural networks.

3. **Training**: Run the training script to train the CNN model on the preprocessed dataset. Adjust hyperparameters and network architecture as needed.

4. **Evaluation**: After training, evaluate the performance of the trained model on a separate test set to assess its accuracy, precision, recall, and other metrics.
   
5. **Inference**: Use the trained model to make predictions on new MRI scans to detect brain tumors. You can either use the provided inference script or integrate the model into your own applications.



