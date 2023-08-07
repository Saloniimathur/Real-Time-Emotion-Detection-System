# Real-Time-Emotion-Detection-System
This is a Real Time Emotion Detection System built using Python and Machine Learning model, CNN

## Overview
This project is an Emotion Detection System that predicts real-time emotions of an individual using Convolutional Neural Networks (CNN). The system has been trained to recognize 7 emotions: angry, sad, happy, neutral, fear, frustrated, excited, and disgust. The model is trained using data collected through the data_collection.py file, then trained and saved using the data_training.py file. Finally, the inference.py file is used for real-time emotion prediction.

## Data Collection
Run the data_collection.py file to collect training data. The programmer can enter the label of the emotion while the system records the user's facial expressions and other relevant features. The data collected is then stored in a .npy file.

## Data Training
Use the data_training.py file to train the Emotion Detection CNN model. The training data collected in the previous step is used to train the model. The trained model is saved as model.h5.

## Real-Time Emotion Prediction
Run the inference.py file to perform real-time emotion detection. The system uses the trained CNN model to analyze the individual's facial expressions and predict their emotions.

![image](https://github.com/Saloniimathur/Real-Time-Emotion-Detection-System/assets/89344753/abfbdff6-36d7-4e81-9850-c3f5294081fa)


![image](https://github.com/Saloniimathur/Real-Time-Emotion-Detection-System/assets/89344753/4a90d8ea-1856-4204-a27c-d5604cb2b8e8)


![image](https://github.com/Saloniimathur/Real-Time-Emotion-Detection-System/assets/89344753/9082fdbb-2902-473f-8856-23b0eead04a4)


![image](https://github.com/Saloniimathur/Real-Time-Emotion-Detection-System/assets/89344753/a8df8d48-ef60-4e35-baa9-d6c30b5fed97)

## Installation
Clone the Repository: Clone this GitHub repository to your local machine using the following command:
bash
Copy code
git clone https://github.com/your_username/emotion-detection-system.git

### How to Use
1. Data Collection: Run data_collection.py and enter the label of the emotion while showing corresponding facial expressions to record the training data.

2. Data Training: Execute data_training.py to train the Emotion Detection CNN model using the collected data. The model will be saved as model.h5.

3. Real-Time Emotion Prediction: Run inference.py to predict the real-time emotion of the individual using the trained CNN model.

## Contributing
Contributions to the Real-Time Emotion Detection System are welcome. If you have any suggestions, improvements, or feature additions, please feel free to submit a pull request.
