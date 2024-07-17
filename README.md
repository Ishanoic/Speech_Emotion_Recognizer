README.md
# Speech Emotion Recognizer

## Overview
The Speech Emotion Recognizer (SER) project aims to classify speech signals into various emotional categories using machine learning techniques. This project utilizes the RAVDESS dataset and focuses on feature extraction using Mel Spectrograms and classification using a multi-class Support Vector Machine (SVM) classifier.

## Features
- **Audio Preprocessing**: Normalizes and converts audio files into spectrograms.
- **Feature Extraction**: Utilizes Mel Spectrograms for extracting features from audio data.
- **Emotion Classification**: Implements a multi-class SVM classifier to categorize emotions.
- **Model Evaluation**: Provides performance metrics to evaluate the classifier.

## Installation
1. Clone the repository:
   ```sh
   git clone [https://github.com/your-username/SpeechEmotionRecognizer.git](https://github.com/Ishanoic/Speech_Emotion_Recognizer)
Navigate to the project directory:

cd SpeechEmotionRecognizer

## Dependencies
Python 3.x
Librosa
Scikit-learn
Matplotlib
NumPy
Pandas

## Dataset
The project uses the Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS). Please download the dataset from RAVDESS and place it in the data directory.

## Results
The trained SVM classifier achieves a notable accuracy in recognizing emotions from speech, with detailed performance metrics provided in the evaluation phase.

Acknowledgements
The RAVDESS dataset creators for providing the audio data.
The open-source community for providing the tools and libraries used in this project.

