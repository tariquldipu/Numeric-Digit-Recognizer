## Handwritten Numeric Digit Recognizer

This python program recognizes handwritten English numeric digit using deep learning techniques.

**Python Version-**  3.9
**Libraries-** Tensorflow, Keras, Pillow, Numpy, Tkinter

Install the necessary python libraries by using the following command on your terminal---

    python3 -m pip install numpy tensorflow keras pillow


This python program will implement a handwritten English numeric digit recognition app using the MNIST dataset. The MNIST dataset is already included inside the keras library. The MNIST dataset contains 60,000 training images of handwritten digits from zero to nine and 10,000 images for testing. The MNIST dataset has 10 different classes. The handwritten digits images are represented as a 28×28 matrix where each cell contains grayscale pixel value. Convolutional Neural Networks (CNN) method is used to train the dataset. Because CNN works really well for image classification problem. The CNN model creation and dataset training is done inside the python file *digit_recognizer_TRAIN.py*. After training, the weights and model definition are saved inside the newly created *mnist.h5* file. The model has around 99% accuracy.


Next, a new graphical user interface (GUI) is created in the *digit_recognizer_GUI.py* python file. The interactive GUI was created using the python Tkinter library. The interactive GUI enables a user to draw a shape (english numeric digit) using mouse cursor on the canvas. And finally it displays the recognized digit with an accuracy percentage. 

Here is a screenshot of the sample examples---
![Handwritten Digit Recognizer](https://github.com/tariquldipu/Covid19-Dashboard/blob/main/Dashboard.png)
