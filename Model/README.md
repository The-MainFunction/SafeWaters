# AI-Driven Disaster Response and Recovery Model

This folder contains the AI model template developed for disaster response and recovery, specifically focusing on analyzing post-disaster satellite images to predict the impact and assist in efficient resource allocation.

## Model Overview

The model leverages Convolutional Neural Networks (CNNs) to analyze satellite images and classify them based on the impact of disasters. The primary objective is to provide real-time, accurate assessments of disaster-affected areas to aid in the coordination of rescue and relief efforts.

### Key Features

- **Image Classification**: The model classifies images into categories based on the type and severity of disaster impact.
- **Resource Allocation**: Predictions from the model help in determining which areas need immediate attention and resources.
- **Real-Time Analysis**: The model is designed to process real-time satellite data for ongoing monitoring and rapid response.

## Dataset Details

The dataset used for training and evaluating the model includes a comprehensive collection of satellite images annotated with relevant information about disaster impact. The dataset is structured as follows:

- **Images Folder**: Contains subfolders for training, validation, and testing images.
  - `Train_Image`
  - `Valid_Image`
  - `Test_Image`
- **Questions Folder**: Contains JSON files with questions, ground truth, and question types for each image.
  - `Training_Question.json`
  - `Valid_Question.json`
  - `Test_Question.json`

### Dataset Inspiration and Link

The dataset and the project are inspired by the [FloodNet Challenge EARTHVISION2021](https://github.com/BinaLab/FloodNet-Challenge-EARTHVISION2021). The dataset used can be accessed via the following link:

- [Dataset Link](https://drive.google.com/drive/folders/1g1r419bWBe4GEF-7si5DqWCjxiC8ErnY)

## Training and Evaluation

The model has been trained with limited resources, focusing on optimizing performance within the constraints. Key steps in the training process include:

1. **Data Preprocessing**: Resizing images, normalizing pixel values, and encoding labels.
2. **Model Architecture**: Using a CNN model tailored for image classification.
3. **Training**: Conducted with a batch size of 32 and 10 epochs.
4. **Evaluation**: The model's performance is evaluated using validation and test datasets, focusing on accuracy and prediction consistency.

## Future Enhancements

- **Scalability**: Enhancing the model to handle larger datasets and real-time data more efficiently.
- **Integration**: Seamless integration with live satellite feeds for continuous monitoring.
- **Resource Optimization**: Improving the model's performance with better computational resources to reduce training and inference times.

This model is a prototype and serves as a foundational step towards developing a robust AI-driven disaster response system that can significantly improve the speed and accuracy of disaster management efforts.

