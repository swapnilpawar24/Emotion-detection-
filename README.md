# Emotion Detection using Convolutional Neural Network
![CNN-layers-in-EmotionDetectionModel](https://github.com/swapnilpawar24/Emotion-detection-/assets/151537409/1b7cf74f-f1b5-4458-bbe7-50c9ace18799)
<img width="363" alt="Screenshot 2024-01-28 201246" src="https://github.com/swapnilpawar24/Emotion-detection-/assets/151537409/53e276a3-179b-4bbf-b8fb-b4ace0b02e5d">


## Overview

This repository contains Python code for building and training a Convolutional Neural Network (CNN) for emotion detection. The model is trained on a dataset consisting of facial images representing different emotions.

## Dataset

The dataset is structured with separate folders for each emotion category. Each folder contains images corresponding to that emotion.

### Folder Structure

- angry/
- disgusted/
- fearful/
- happy/
- neutral/
- sad/
- surprised/


## Clone the repository:
`https://github.com/swapnilpawar24/Emotion-detection-.git`
   
## Model Architecture
The CNN model consists of multiple convolutional layers, batch normalization, activation functions, and fully connected layers. It is compiled using the Adam optimizer and categorical crossentropy loss.

## Training and Evaluation
The model is trained using data augmentation on the training set and evaluated on a separate testing set. Training history, including loss and accuracy over epochs, is visualized using matplotlib.

#### Author
Swapnil Pawar
