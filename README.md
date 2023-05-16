# Emotion Classification through Audio Data

This project aims to build a deep learning model for emotion detection/classification using audio data. The model will be trained to analyze audio files and predict the corresponding emotional state.

## Project Overview
The main components of this project are as follows:

### Extracting Audio Features: 
We have implemented an extract_feature function that utilizes various other functions to extract relevant information from audio files. These features will serve as input to the emotion classification model.

### Emotion Classification Model: 
We employ the MLPClassifier from the scikit-learn library to train our deep learning model. The MLPClassifier is a multi-layer perceptron that enables us to classify audio data into different emotion categories.

### Web Application Development: 
In addition to the model, we will create a web application using the Django framework. This application will provide a user-friendly interface for users to upload and classify their audio files, obtaining the predicted emotions. The web application will be hosted on AWS (Amazon Web Services) for seamless accessibility.

## Repository Structure

- /data: Contains sample audio files for testing the model.
- /models: Includes the trained emotion classification model.
- /src: Source code directory.
  - audio_utils.py: Helper functions for audio feature extraction.
  - model_training.py: Script for training the emotion classification model.
  - web_app.py: Django web application implementation.
- /templates: HTML templates for the web application.
- README.md: Documentation about the project.

## Getting Started
To get started with the project, follow these steps:

- Clone the repository: git clone <repository_url>
- Install the necessary dependencies: pip install -r requirements.txt
- Train the emotion classification model: python src/model_training.py
- Start the web application: python src/web_app.py
- Access the web application in your browser: http://localhost:8000

## Contributing
We welcome contributions to improve and enhance this project. If you have any suggestions or would like to report an issue, please feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. You are free to modify and use the code as per the terms of this license.

## Acknowledgments
We would like to acknowledge the contributions and resources from the open-source community and the libraries utilized in this project.
