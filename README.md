# SafeWaters


## AI-driven Disaster Response and Recovery


### Problem Statement

In the aftermath of a disaster, rapid response and efficient recovery are crucial to minimize the impact on affected communities. Traditional methods of assessing damage and coordinating relief efforts can be slow and resource-intensive. This project aims to develop an AI-driven system to automate and streamline the disaster response and recovery process, leveraging satellite imagery and other data sources to provide real-time insights and support decision-making.

### Understanding the Problem Statement

Disasters such as cyclones can cause widespread destruction, requiring immediate action to save lives and restore normalcy. In states like Odisha and West Bengal, cyclones have historically caused significant damage to infrastructure and livelihoods. This project aims to address the challenges faced during the aftermath of such disasters by utilizing AI to analyze satellite images and predict the extent of damage, helping officials to allocate resources more effectively.

### Brief Explanation of the Approach

Our approach involves using a combination of satellite imagery and machine learning techniques to develop a predictive model for assessing disaster impact. The model will classify images into different categories based on the severity of damage and provide actionable insights to aid in recovery efforts.

### Detailed Proposal

The project is divided into several key components:
1. Data Collection: Acquiring and preparing satellite imagery datasets.
2. Data Preprocessing: Cleaning and preprocessing the images and associated metadata.
3. Model Development: Building and training a CNN model for image classification.
4. Validation and Testing: Evaluating the model's performance on validation and test datasets.
5. Deployment: Integrating the model into a user-friendly interface for real-time monitoring and decision-making.

### Detailed Solution Approach

1. **Data Collection**: We use satellite imagery datasets that include images before and after a disaster, along with annotations describing the damage levels.
2. **Data Preprocessing**: Images are resized and normalized to ensure consistency. Labels are encoded to match the classification categories used in the model.
3. **Model Development**: A convolutional neural network (CNN) is designed to analyze the images and predict the damage category. The model is trained using labeled data and validated on a separate dataset.
4. **Validation and Testing**: The model's performance is evaluated using standard metrics like accuracy, precision, and recall. Predictions on new images are compared with ground truth to assess the model's reliability.
5. **Deployment**: The trained model is deployed as part of a mobile application prototype, providing real-time insights to disaster response teams.

### Tools and Devices Used in Development

- **Data Processing**: Python, OpenCV, pandas, numpy
- **Model Development**: TensorFlow, Keras
- **Data Visualization**: Matplotlib, Seaborn
- **User Interface**: Prototyped using design tools (Figma, Adobe XD)
- **Dashboard**: Qlik Insights for post-disaster impact visualization

### Technologies Involved

- Convolutional Neural Networks (CNN)
- Image Processing
- Machine Learning
- Data Visualization
- Cloud Computing (for model deployment)

### Dataset Description

The dataset used for this project includes satellite images categorized into different folders for training, validation, and testing. Each image is associated with a JSON file containing questions and ground truth labels describing the damage. This aligns with our project vision by providing the necessary data to train and validate our model, ensuring it can accurately predict disaster impact.

### Project Structure

The project is organized into the following folders:

- **Data**: Contains the post-disaster impact dashboard made using Qlik Insights and the dataset used for the dashboard (acquired from data.gov.in).
- **Model**: Contains the current state of the model development, including the code for preprocessing, training, and validation. It also includes a separate data exploration file that provides insights into the dataset.
- **UI**: Contains prototype design image ideas for the mobile application, which officials can use to monitor resource allocation and other critical information during disaster response.

#### Accessing the Files

- **data**: 
  - `post_disaster_impact_dashboard.qvf` (Qlik Insights dashboard)
  - `dashboard_dataset.csv` (Dataset used for the dashboard)
- **model**: 
  - `cnn_model.ipynb` (Current model development notebook)
  - `data_exploration.ipynb` (Data exploration notebook)
- **UI**: 
  - `ui_prototype_designs.png` (Prototype design images for the mobile app)

### Getting Started

1. Clone the repository.
2. Navigate to the `model` folder and open `cnn_model.ipynb` to start working on the model.
3. Use the `data_exploration.ipynb` notebook to understand the dataset and preprocessing steps.
4. Refer to the `UI` folder for design ideas and integrate them into the final application.

### Contributing
We welcome contributions to improve this project. Please fork the repository and submit pull requests for any enhancements or bug fixes.

