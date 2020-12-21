# Handwritten-Digit-Recognition-MNIST-with-CNN-in-Python-using-Keras
This project implements and explains Python code to detect handwritten digits (MNIST dataset) with a CNN using Keras.  

#### Objective
- Understand how CNN helps by implementing first with MLP and then moving onto CNN
- Get a idea about CNN implementation in Python / Keras

#### Gratitude
I am reading the book **'Deep Learning with Python' by Francois Chollet**. I sincerely express my gratitude to the author for the simplicity in explanation and explanation with code for MLP/CNN based solution for Handwritten Digit Recognition using MNIST dataset. 

I understood the code from the book and thought to write it myself in this notebook to build my understanding and intuition. I thought this way I can capture my inferences as I am reading the book and get an idea about how CNN works.

#### Key Design Considerations
This is a Multi-Class Classification problem (10 classes)
- Language: Python
- Deep Learning Package: Keras
- Dataset: MNIST dataset available with Keras
- Model: MLP, CNN

#### Key Results
MLP based solution
- Input (784x1 coumn vector) -> 1 hidden layer (512 neurons, relu) -> Output (10 classes, softmax)
- Training Accuracy = **~98.9%**
- Test Accuracy = **~97.9%**
