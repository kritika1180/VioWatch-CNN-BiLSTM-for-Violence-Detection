# VioWatch-CNN-BiLSTM-for-Violence-Detection

## Overview

This project focuses on developing a robust surveillance solution for detecting violence in surveillance videos. Leveraging aria2 for streamlined data access, the project conducts frame extraction as a preprocessing step, optimizing dataset preparation for subsequent implementation. The implemented CNN-BiLSTM architecture in TensorFlow achieves a remarkable 97% accuracy in violence detection, showcasing strong technical proficiency and achievement in developing robust surveillance solutions.

## Technologies Used

- **aria2**: Utilized for streamlined data access, facilitating efficient data retrieval for processing.
- **TensorFlow**: Employed for implementing the CNN-BiLSTM architecture, a powerful deep learning framework for training and testing the violence detection model.
- **OpenCV**: Used for frame extraction, a crucial preprocessing step in video analysis.

## Implementation Details

### Data Acquisition and Preprocessing

- Leveraged aria2 for efficient data access, ensuring smooth retrieval of surveillance videos.
- Conducted frame extraction from videos using OpenCV, preparing the dataset for model training.

### Model Architecture

- Implemented a Convolutional Neural Network (CNN) combined with a Bidirectional Long Short-Term Memory (BiLSTM) architecture in TensorFlow.
- The CNN extracts spatial features from video frames, while the BiLSTM captures temporal dependencies, enhancing the model's ability to recognize patterns over time.

### Model Training and Evaluation

- Trained the CNN-BiLSTM model on the prepared dataset, optimizing hyperparameters for performance.
- Achieved a remarkable 97% accuracy in violence detection during evaluation, showcasing the effectiveness of the developed solution.

## Future Work

The project aims to explore the integration of an attention mechanism (novelty2.ipynb) into the CNN-BiLSTM architecture. This addition could enhance the model's ability to focus on relevant spatiotemporal features in surveillance videos, potentially improving its performance in violence detection tasks. Future iterations of the project will investigate and implement attention mechanisms to further advance the surveillance solution.

## Usage

1. **Data Preparation:**
   - Ensure the surveillance video dataset is accessible and organized.
   - Utilize aria2 for efficient data retrieval if necessary.
   - Preprocess the data by extracting frames from the videos.

2. **Model Training:**
   - Implement the CNN-BiLSTM architecture in TensorFlow.
   - Train the model using the prepared dataset, adjusting hyperparameters as needed.

3. **Evaluation:**
   - Evaluate the trained model on a separate test dataset to assess its performance.
   - Analyze the accuracy and other relevant metrics to gauge the effectiveness of the violence detection system.

## Conclusion

By leveraging advanced techniques such as aria2 for data access and the CNN-BiLSTM architecture for modeling, this project demonstrates strong technical proficiency and achievement in developing robust surveillance solutions. The achieved 97% accuracy in violence detection underscores the effectiveness of the proposed approach in enhancing security and safety through automated surveillance systems.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, or distribute it as per the terms of the license.
