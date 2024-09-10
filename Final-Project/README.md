# Image Classification using Convolutional Neural Networks (CNN)

This project is part of my Bytewise ML Fellowship and involves developing a Convolutional Neural Network (CNN) model to classify images into different categories. The task includes data preprocessing, model implementation, training, evaluation, and additional challenges like data augmentation and fine-tuning a pre-trained model.

## Dataset

The dataset used for this project is sourced from Kaggle:
[Images Dataset](https://www.kaggle.com/datasets/pavansanagapati/images-dataset)

## Task Overview

### 1. Collect Dataset
A dataset of images belonging to different categories was collected from Kaggle. The dataset contains images in various subfolders, including bike, cars, cats, dogs, flowers, horses, and humans.

### 2. Preprocess Images
The images were preprocessed and resized to a standard size to ensure uniformity. This step included converting images to a consistent format and normalizing pixel values.

### 3. Implement CNN Model
A Convolutional Neural Network (CNN) model was implemented using TensorFlow. The model architecture was designed to effectively capture features from images and classify them into respective categories.

### 4. Train the Model
The CNN model was trained on the preprocessed images. The training process involved splitting the dataset into training and validation sets, optimizing model parameters, and tuning hyperparameters.

### 5. Evaluate Model Performance
The performance of the trained model was evaluated using various metrics, including accuracy, precision, recall, and F1-score. These metrics provided insights into the model's effectiveness in classifying images.

## Additional Challenges

### 1. Data Augmentation
To enhance the model's performance and increase the size of the dataset, data augmentation techniques were applied. This included random rotations, flips, and shifts to create variations of existing images.

### 2. Fine-tune Pre-trained Model
A pre-trained CNN model, specifically VGG16, was fine-tuned on the dataset. This involved leveraging the pre-trained model's feature extraction capabilities and adjusting the final layers to adapt to the specific image categories.


## Conclusion

This project demonstrates the process of developing a CNN model for image classification, including data preprocessing, model implementation, training, and evaluation. The additional challenges of data augmentation and fine-tuning a pre-trained model were successfully addressed, and a simple frontend-backend system was implemented to test the model's functionality.