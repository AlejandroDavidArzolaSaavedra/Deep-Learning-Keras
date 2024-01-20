<h1 align="center">📄 Neural Network Experimentation Iris - Keras</h1>

<img align="left" width="250" height="180" src="https://i.imgur.com/RsmO2hP.gif?raw=true"></a>
This practice aims to explore and compare different hyperparameter configurations in neural networks applied to the Iris dataset.

We will experiment with variables such as the number of layers 🏗️, the number of neurons per layer 🤖, activation functions ⚡, optimizer 🚀, loss function 📉, number of epochs ⏳, batch size 📦, among others.
<div id="user-content-toc">
  <ul>
    <summary><h2 style="display: inline-block">Let the experiments begin! 🚀🔬💻</h2></summary>
  </ul>
</div>

# 👥 Development Team (Ctrl + Click to view profiles)

[![GitHub](https://img.shields.io/badge/GitHub-Andrea%20Santana%20Lopez-purple?style=flat-square&logo=github)](https://github.com/AndreaSantalos)

[![GitHub](https://img.shields.io/badge/GitHub-Alejandro%20David%20Arzola%20Saavedra-blue?style=flat-square&logo=github)](https://github.com/AlejandroDavidArzolaSaavedra)


## Iris Dataset 🌷

The Iris dataset consists of three classes of flowers:

<ul align="center">		
  <a href="https://www.kaggle.com/datasets/uciml/iris" target="_blank">
    <img width="800px"  src="https://i.imgur.com/LoELZjM.png">
  </a>
</ul>

## 📖 Used Libraries

[![Pandas](https://img.shields.io/badge/Pandas-%23191919?style=for-the-badge&logo=pandas)](Link_To_Your_Pandas_Page)
[![Keras](https://img.shields.io/badge/Keras-%23D00000?style=for-the-badge&logo=keras)](Link_To_Your_Keras_Page)
[![scikit-learn](https://img.shields.io/badge/scikit_learn-%23191919?style=for-the-badge&logo=scikit-learn)](Link_To_Your_Scikit_Learn_Page)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-black?style=for-the-badge&logo=tensorflow)](Link_To_Your_TensorFlow_Page)
[![JSON](https://img.shields.io/badge/JSON-%23000000?style=for-the-badge&logo=json)](Link_To_Your_JSON_Page)
[![NumPy](https://img.shields.io/badge/NumPy-%23013243?style=for-the-badge&logo=numpy)](Link_To_Your_NumPy_Page)

## Hyperparameter Experimentation

Experimentation will be conducted with the following variables:

1. **Number of layers:** Different configurations of hidden layers will be tested.
2. **Number of neurons per layer:** The number of neurons in each hidden layer will vary.
3. **Activation functions:** Different activation functions such as ReLU, sigmoid, tanh, among others, will be evaluated.
4. **Optimizer:** Comparisons will be made with optimizers like SGD, Adam, RMSprop, among others.
5. **Loss function:** Various loss functions such as categorical crossentropy, mean squared error, etc., will be tested.
6. **Number of epochs:** The number of epochs during training will vary.
7. **Batch size:** Different batch sizes will be experimented with.

## Best Configurations and Analysis

Configurations that offered the best performance were those with a higher number of hidden layers and intermediate neurons, using the ReLU activation function, the Adam optimizer, categorical crossentropy loss function, a higher number of epochs, and a moderate batch size.

It was observed that more complex and deeper neural network configurations resulted in better performance, especially for the Iris versicolor and Iris virginica datasets.

## How to Run the Experimentation

To run the experimentation and perform tests, follow these steps:

1. Clone this repository to your local machine:
```bash
git clone <https://github.com/AlejandroDavidArzolaSaavedra/practicas_fsi/edit/Deep-Learning-Keras-Iris>
```
2. Navigate to the practice directory:
```bash
cd deepLearningKeras
```
3. Run the main program with the modified files:
```bash
python Keras_iris.ipynb
```

Observe the results of the tests and comparisons between different hyperparameter configurations. Experiment and adjust to achieve the best results!

# 🤝 Contributions
<img align="left" width="120" height="160" src="https://github.com/AlejandroDavidArzolaSaavedra/Deep-Learning-Keras-Iris/assets/90756437/94ff686a-acbe-43fd-9475-ec95af174b20">
If you wish to contribute to this project, feel free to do so. You can open issues or send pull requests to improve the code or add new features. Your collaboration is welcome!
