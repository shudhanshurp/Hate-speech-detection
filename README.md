# Hate Speech Detection

This repository contains a project focused on detecting hate speech through audio analysis and sentiment analysis. The project leverages the SpeechRecognition and PyAudio libraries for audio processing and employs a sophisticated machine learning model for sentiment analysis.

## Project Components

- **Speech to Text**: Converts audio input to text using the SpeechRecognition library.
- **Sentiment Analysis**: Utilizes a Bidirectional LSTM model to classify the sentiment of the text. The model was trained on a dataset with 25,000 entries, balanced via oversampling techniques, and achieved an accuracy of 88% on the test dataset.

## Setup

1. Install the required Python packages:
```bash
pip install SpeechRecognition pyaudio numpy pandas keras sklearn
```

2. Run the Jupyter notebook for detailed steps:
```bash
jupyter notebook speechToText.ipynb
```
