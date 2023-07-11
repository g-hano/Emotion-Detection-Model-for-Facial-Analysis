# Emotion-Detection-Model-for-Facial-Analysis

This is a Python program for emotion detection on the face using the TensorFlow framework with Keras. The program utilizes a deep learning model to classify emotions into four categories: "happy", "sad", "angry", and "neutral". The model architecture consists of a sequential neural network with three layers.

### Resizing and Greyscaling Images
![Resizing Images](https://i.imgur.com/nC9dmwe.png)

### Predicts
![Predict Result](https://i.imgur.com/qK9oCrD.png)

## Model Architecture
The model is built using the following layers:

- **Input Layer:** The input layer is a 2D array of shape (50, 50, 3), representing the image dimensions (height, width, and color channels).

- **Hidden Layer:** This layer is a fully connected dense layer with 16 neurons and uses the Rectified Linear Unit (ReLU) activation function.

- **Output Layer:** The output layer consists of four neurons, corresponding to the four emotion classes. It uses the softmax activation function to output probabilities for each class.

The model is implemented using the TensorFlow library with the Keras API.

## Dataset
The program was trained and tested on a dataset comprising a total of 202 images. The dataset was collected from Pexels and Pinterest. The images were preprocessed by resizing them to 50x50 and converting them to grayscale. The dataset was labeled using Tzutanin's LabelImg.

## Accuracy
The trained model achieved an accuracy of **0.4 on the test dataset**. It's important to note that the accuracy may vary depending on the specific dataset and the complexity of emotions captured in the images. This is my first computer vision project where I wrote everything in code without using websites or apps.

## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, feel free to create a pull request or submit an issue.

## Acknowledgments
This project was inspired by the field of computer vision and emotion recognition. Special thanks to [Nicholas Nenotte](https://github.com/nicknochnack) for his amazing tutorials. I would also like to thank the creators and contributors of TensorFlow and Keras for their excellent libraries.
