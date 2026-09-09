# Speech Command Recognition Using LSTM

## Overview

This project develops a deep learning model for recognizing spoken
commands from short audio recordings using a Long Short-Term Memory
(LSTM) neural network.
(https://www.kaggle.com/datasets/neehakurelli/google-speech-commands/data()


The project focuses on transforming raw speech signals into
machine-learning-ready features using Mel-Frequency Cepstral
Coefficients (MFCCs), followed by sequence modelling using an LSTM
architecture for multi-class speech command classification.

The complete workflow covers audio preprocessing, feature extraction,
model development, training, evaluation, and prediction on unseen
audio samples.


## Objectives

The main objectives of this project are to:

- Process and prepare speech command audio recordings for machine
  learning.
- Extract MFCC features from speech signals.
- Develop an LSTM-based deep learning model for speech command
  classification.
- Evaluate model performance using appropriate classification metrics.
- Analyze classification performance using training curves and a
  confusion matrix.
- Test the trained model using previously unseen audio recordings.


## Dataset

The project uses a speech command dataset obtained from Kaggle.

The dataset contains short audio recordings representing different
spoken commands. Each audio file belongs to a predefined command
class.

### Dataset Characteristics

- **Data type:** Audio / Speech
- **File format:** WAV
- **Task:** Multi-class classification
- **Feature representation:** MFCC
- **Model:** LSTM
- **Dataset source:** Kaggle

The original dataset is not included in this repository due to its
size. The notebook contains the preprocessing and feature extraction
workflow used for preparing the dataset.


## Methodology

The overall workflow of the project is:

```text
Speech Audio Files
        ↓
Audio Loading
        ↓
Audio Preprocessing
        ↓
MFCC Feature Extraction
        ↓
Feature Padding / Sequence Preparation
        ↓
Training / Validation / Test Split
        ↓
LSTM Model Development
        ↓
Model Training
        ↓
Performance Evaluation
        ↓
Prediction on Unseen Audio
