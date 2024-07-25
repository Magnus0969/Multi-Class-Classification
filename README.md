# Multi-Class-Classification Using Keras & VG16
This repository contains a project focused on multiclass classification of images using the Keras library and the VGG16 pre-trained model. The primary objective is to accurately classify images into multiple categories using a convolutional neural network (CNN) model fine-tuned for this specific task.

# Features
Data Augmentation: Utilizes Keras' ImageDataGenerator for data augmentation, including rescaling, rotation, shifting, shearing, zooming, and horizontal flipping.
Transfer Learning: Implements the VGG16 model pre-trained on ImageNet, with custom top layers added for the classification task.
Model Fine-tuning: Freezes the initial layers of VGG16 and fine-tunes the last few layers to adapt the model to the new dataset.
Training and Validation: Splits the dataset into training and validation sets to evaluate the model's performance during training.
Evaluation Metrics: Includes model evaluation using loss and accuracy metrics, along with a detailed classification report.

# Results
The model achieves notable accuracy on the validation set, demonstrating effective multiclass classification capabilities. Detailed performance metrics and a classification report are provided in the notebook.

# Contributing
Contributions are welcome! Feel free to submit issues or pull requests to enhance the project.
