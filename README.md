# goit_DS_ML_Hw-09
# Fashion MNIST Classification with Keras

This project demonstrates the implementation and comparison of different neural network architectures using **Keras** for the **Fashion MNIST image classification task**.

## Models

Several neural network architectures were tested:

* Baseline Dense Neural Network
* Improved Dense Network with GELU activation
* Convolutional Neural Network (CNN)

## Results

The baseline Dense model provided a good starting point with an accuracy of approximately **86.24%**.

Further improvements to the Dense architecture resulted in a small performance increase. However, the **Convolutional Neural Network (CNN)** achieved the best result:

**CNN Test Accuracy: 92.16%**

## Conclusion

Increasing the complexity of a standard Dense network produced only a modest improvement.

The CNN performed significantly better because convolutional layers can capture the spatial structure and local patterns of images.

Therefore, **CNN was the most suitable architecture for the Fashion MNIST image classification task**.

## 🛠 Technologies

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Fashion MNIST

