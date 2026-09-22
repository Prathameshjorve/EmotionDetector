# EmotionDetector

# Emotion Detector

## Project Overview

Emotion Detector is an AI-based web application that analyzes a text statement and identifies the emotions expressed in it.

The application uses the Watson NLP Emotion Prediction service to detect five different emotions:

- Anger
- Disgust
- Fear
- Joy
- Sadness

The application also identifies the **dominant emotion** expressed in the given text.

## Features

- Emotion detection from text
- Detection of anger, disgust, fear, joy, and sadness
- Identification of the dominant emotion
- Flask-based web interface
- Error handling for invalid or blank input
- Unit testing
- Static code analysis using PyLint
- Simple and user-friendly interface

## Technologies Used

- Python
- Flask
- Watson NLP
- Requests
- HTML
- CSS
- JavaScript
- Unittest
- PyLint

## Project Structure

```text
EmotionDetector/
│
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
│
├── templates/
│   └── index.html
│
├── LICENSE
├── README.md
├── requirements.txt
├── server.py
└── test_emotion_detection.py
