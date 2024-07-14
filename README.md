# Gesture Recognition Case study IIITB Assignment [![](https://img.shields.io/badge/Prateek-Ralhan-brightgreen.svg?colorB=ff0000)](https://prateekralhan.github.io/)


Developed by:
1. Sai Anuraag Gampa (https://github.com/anuraaggampa)

### Problem Statement

As a data scientist at a home electronics company specializing in state-of-the-art smart televisions, you aim to develop an innovative feature enabling the TV to recognize five distinct gestures performed by users. This feature will allow users to control the TV without a remote.

The TV's webcam continuously monitors these gestures, each corresponding to a specific command:

| Gesture      | Corresponding Action           |
|--------------|---------------------------------|
| Thumbs Up    | Increase the volume             |
| Thumbs Down  | Decrease the volume             |
| Left Swipe   | 'Jump' backwards 10 seconds     |
| Right Swipe  | 'Jump' forward 10 seconds       |
| Stop         | Pause the movie                 |

Each video sequence consists of 30 frames (or images).

### Objectives:

1. **Generator**: Ensure the generator can process a batch of videos as input without any errors. It should successfully handle steps like cropping, resizing, and normalization.
2. **Model**: Develop a model capable of training without errors, judged by the total number of parameters (to ensure minimal inference time) and the accuracy achieved. Start with a small dataset for initial training before expanding.
3. **Write-up**: Provide a detailed procedure for selecting the final model. Begin with the rationale for choosing the base model, followed by an explanation of the reasons and metrics considered in the modifications and experiments leading to the final model selection.

I chose a CNN+LSTM based model for its reasonable accuracy given the data type and the need for a lightweight model.

