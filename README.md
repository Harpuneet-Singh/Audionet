# Audionet

This project classifies guitar notes using deep learning.
You find the core logic in `Audionet_Final.ipynb`.
The pipeline processes raw audio with Librosa to generate Mel-Spectrograms.
You feed these spectrograms into a Convolutional Neural Network (CNN).
The model identifies notes ranging from A2 to G#5.
It achieves 96.9% accuracy on the test set.
You see the use of `categorical_crossentropy` loss and the Adam optimizer.
The dataset undergoes normalization and resizing to 128x128 dimensions before training.
This notebook serves as the end-term evaluation project.
