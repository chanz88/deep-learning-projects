# CNN Image Classification
A Convolutional Neural Network (CNN) project to classify vegetable images into four categories: Broccoli, Carrot, Cucumber, and Tomato.

## Dataset used
This project uses an image dataset containing 2000 vegetable images, with 500 images for each class: Broccoli, Carrot, Cucumber, and Tomato. The dataset is balanced across all classes.

The target variable is the vegetable class, which is encoded into 4 categories and converted to one-hot format.

## What I Did
- Loading images from class folders
- Image preprocessing (resize to 64x64, grayscale conversion, pixel normalization to 0-1)
- Train, validation, and test split (80% / 10% / 10%)
- One-hot encoding for the labels
- Building a CNN model with Keras (2 Convolutional layers, 2 Max Pooling layers, and Dense layers)
- Training the model with Adam optimizer and categorical crossentropy loss (30 epochs, batch size 32)
- Model evaluation on the test set
- Confusion matrix and classification report
- Comparing actual vs predicted labels on test images
- Visualizing training and validation accuracy and loss curves
