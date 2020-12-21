# MNIST-Handwritten-Digit-Recognition-with-CNN-in-Python-using-Keras
This project implements and explains Python code to detect handwritten digits (MNIST dataset) with a CNN using Keras.  

#### Objective
- Understand how CNN helps by implementing first with MLP and then moving onto CNN
- Get an idea about CNN implementation in Python / Keras

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
**MLP based solution**
- Input (784x1 column vector) -> 1 hidden layer (512 neurons, relu) -> Output (10 classes, softmax)
- Number of paramters = **407050**
- Training Accuracy = **~98.9%**
- Test Accuracy = **~98.0%**


**CNN based solution**
- Input (28x28x1 matrix) -> Conv(32 3x3 filters, relu) -> Maxpool(2x2) -> Conv(64 3x3 filters, relu) -> Maxpool(2x2) -> Conv(64 3x3 filters, relu) -> Flatten to a column vector for FCN -> FCN (64 outputs, relu) -> FCN (10 outputs, softmax)
- Number of paramters = **93322**
- Training Accuracy = **~99.4%**
- Test Accuracy = **~99.3%**

#### Conclusion
CNN has the advantage of using the spatial information in the image as compared to MLP, hence achieves better accuracy with reduced parameters.
