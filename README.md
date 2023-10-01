# Malaria Cell Image Classification using Convolutional Neural Networks (CNN)

## Project Overview

This project aims to classify cell images into one of two classes: uninfected or parasitized, to aid in the detection of Malaria. The model was built using Convolutional Neural Networks (CNN) and achieved an accuracy of 91%.

![Malaria Cell Classification](https://thepythoncode.com/media/articles/malaria-cells-classification/malaria-classification-test-cells.png)


## Model Architecture

The CNN model used in this project follows a specific architecture consisting of alternating Convolutional layers and MaxPooling layers. The architecture can be summarized as follows:

- Convolutional Layer (Conv1)
- MaxPooling Layer (MaxPool1)
- Convolutional Layer (Conv2)
- MaxPooling Layer (MaxPool2)
- Convolutional Layer (Conv3)
- MaxPooling Layer (MaxPool3)

After passing through these layers, the data was flattened and then passed through a Dense layer to finalize the classification.

## Results

The model achieved an accuracy of 91% on the test dataset. This demonstrates its capability to reliably classify malaria cell images into either 'Uninfected' or 'Parasitized' categories.



