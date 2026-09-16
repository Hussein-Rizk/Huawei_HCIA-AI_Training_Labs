# 🤖 Huawei HCIA-AI Training Labs — 2022

A collection of practical **Machine Learning and Deep Learning laboratory exercises** completed during **Huawei HCIA-AI training in 2022**.

The notebooks progress from classical machine-learning methods to neural networks, computer vision, and time-series forecasting using **Python, NumPy, Scikit-learn, TensorFlow, and Keras**.

> **Note:** These files are presented as training/lab exercises rather than original standalone research projects. Some notebooks are based on or adapted from educational examples and tutorials referenced inside the notebooks.

---

## 🎓 Certificate

<p align="center">
  <a href="./HCIA-AI%20Certificate.pdf">
    <img src="./HCIA-AI%20Certificate.png"
         alt="HCIA-AI Certificate"
         width="80%">
  </a>
</p>

<p align="center">
  <b>Click the certificate to view the original PDF.</b>
</p>

---

## 📚 Topics Covered

```text
Linear Regression
      ↓
Logistic Regression
      ↓
Decision Trees
      ↓
Multilayer Perceptrons
      ↓
Convolutional Neural Networks
      ↓
LSTM Time-Series Forecasting
```



---

# 📈 Classical Machine Learning

## `Lab2.ipynb` — Linear Regression

Introduces **linear regression** using three approaches:

- manual implementation with NumPy
- gradient-descent optimization
- Scikit-learn `LinearRegression`
- a simple Keras Dense model with linear activation

The notebook visualizes the data and loss behavior, fits the regression model, and performs predictions.

---

## `Lab04_Logistic_regression.ipynb` — Logistic Regression

Demonstrates **binary classification** using MNIST digits **0 and 1**.

Main steps include:

- loading MNIST
- filtering the dataset to two classes
- flattening `28 × 28` images into 784-dimensional vectors
- pixel normalization
- training a single sigmoid output neuron
- binary cross-entropy loss
- model evaluation

The notebook also contains a confusion-matrix example.

---

## `Lab05_Decision_Tree(Gh).ipynb` — Decision Tree Classification

Uses the **Iris dataset** to demonstrate a Decision Tree classifier.

The notebook includes:

- train/test splitting
- `DecisionTreeClassifier`
- limiting tree depth
- classification and accuracy evaluation
- Graphviz tree visualization
- sample predictions
- saving the trained model with `pickle`

---

# 🧠 Neural Networks

## `MLP_boston.ipynb` — MLP for House-Price Regression

Uses the Keras **Boston Housing** dataset to demonstrate regression with a multilayer perceptron.

The workflow includes:

- feature standardization
- a neural network with Dense and Dropout layers
- training over multiple epochs
- MSE/loss visualization
- test evaluation
- model prediction
- saving the trained Keras model

---

## `MLP_mnist.ipynb` — MLP for MNIST Classification

Builds a feed-forward neural network for handwritten digit recognition.

The notebook:

- loads MNIST
- reshapes each `28 × 28` image into 784 features
- uses Dense layers with ReLU activations
- applies a 10-class Softmax output
- trains and evaluates the classifier

---

# 👁️ Computer Vision

## `cnn_CIFAR10.ipynb` — CNN Image Classification

Demonstrates a **Convolutional Neural Network** for CIFAR-10 image classification.

The notebook includes:

- CIFAR-10 loading and normalization
- visualization of sample images
- Conv2D layers
- MaxPooling layers
- Dense classification layers
- Adam optimization
- training/validation accuracy plots
- final test evaluation

The notebook itself identifies this material as a TensorFlow educational tutorial and includes its original attribution/license information.

---

# 📉 Time-Series Forecasting

## `Keras_LSTM_stock_price.ipynb` — Tesla Stock Forecasting with LSTM

Implements an **LSTM-based time-series forecasting model** using historical Tesla stock data.

The notebook includes:

- loading `TSLA.csv`
- train/test separation
- Min-Max scaling
- creation of 60-step input sequences
- stacked LSTM layers
- Dropout regularization
- prediction of future stock values
- comparison of real and predicted prices

The notebook contains a reference to the educational article from which the exercise was based/adapted.

### `TSLA.csv`

Historical Tesla market data used by the LSTM notebook, containing columns such as:

- Date
- Open
- High
- Low
- Close
- Adjusted Close
- Volume

---

# 🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow
- Keras
- Graphviz
- Pickle

---

# 🎓 Training Information

**Program:** Huawei HCIA-AI Training  
**Year:** 2022  
**Type:** Machine Learning & Deep Learning Training Labs

---

## 🚀 What This Repository Demonstrates

This repository documents hands-on practice with:

- supervised learning
- regression
- binary and multi-class classification
- decision-tree models
- neural networks
- deep learning
- image classification
- time-series modeling
- data preprocessing
- model evaluation
- model visualization
- model persistence

It represents the practical AI exercises completed during the Huawei HCIA-AI training program in 2022.
