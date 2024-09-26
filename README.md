# Face-mask-recognition

In response to the global COVID-19 pandemic and the implementation of worldwide lockdowns, wearing face masks became mandatory in public spaces. This repository contains a deep learning-based approach to detecting faces with and without masks using a custom Convolutional Neural Network (CNN) model.

The dataset used for this project consists of 7,553 RGB images divided into two categories: with_mask and without_mask. The model was trained and achieved 94% accuracy on the training set and 96% accuracy on the validation set.

**Dataset**

The dataset contains 7,553 images split across two folders:

with_mask: 3,725 images
without_mask: 3,828 images
All images are in RGB format and contain faces either wearing or not wearing a mask. The images are labeled accordingly and stored in their respective folders.

**Model**
A custom CNN architecture was developed to train on the face mask dataset. The training and validation accuracies are as follows:

Training Accuracy: 94%
Validation Accuracy: 96%
This model is capable of accurately distinguishing between individuals wearing and not wearing face masks in real-world images.

# Getting Started

**Prerequisites**

Ensure you have the following libraries installed:

pip install tensorflow keras numpy pandas matplotlib

**Clone the Repository**

```git clone https://github.com/ramvisweshvar/face-mask-detection.git
cd face-mask-detection```


**Training the Model**

You can train the model using the provided dataset by running the following script:

```python train_model.py```

This script will load the dataset, preprocess the images, and train the CNN model.

# Results

After training, the model achieves the following results:

**Training Accuracy**: 94%
**Validation Accuracy**: 96%

The trained model can be used for face mask detection in real-time applications or for further fine-tuning.
