Gender Voice Identification using RNN (Deep Learning)


Overview:

This project is a gender voice identification system implemented using Recurrent Neural Networks (RNN) and deep learning techniques. The goal is to classify audio samples as either male or female based on their acoustic features. This system can have applications in various fields, including voice-controlled systems, automatic speaker recognition, and more.

Features:

Data Preprocessing: Audio data (in WAV format) is preprocessed to extract relevant features, including MFCCs, chroma, and mel-frequency cepstral coefficients.

RNN Model: An LSTM-based Recurrent Neural Network is trained to learn and classify audio samples based on their extracted features.

Data Augmentation: Data augmentation techniques are applied to improve model generalization.

Early Stopping: The model uses early stopping to prevent overfitting and improve training efficiency.

Model Evaluation: The model is evaluated on a separate test dataset to measure its accuracy.

Usage:

Install the necessary dependencies by running pip install -r requirements.txt.

Train the model using your audio dataset and the provided Jupyter Notebook.

Save the trained model as gender_voice_identification_model.h5.

Use the model for gender classification on new audio samples.

Contributors
Aman Jawalekar
https://www.kaggle.com/datasets/mozillaorg/common-voice

License
This project is licensed under the MIT License.

Acknowledgments
Special thanks to Librosa for its audio analysis and feature extraction capabilities.