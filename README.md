# 🪻Iris RBFN (Radial Basis Function Network) Prediction And EDA🌷

## 📋 Project Overview

This project demonstrates flower species classification using the Iris dataset and a Radial Basis Function (RBF) Neural Network. It leverages machine learning and deep learning techniques to distinguish between different iris flower types with high accuracy.

## ✨ Key Features

- 🔍 Advanced classification on Iris dataset
- 🧠 Custom RBF (Radial Basis Function) layer implementation
- 🛠 Comprehensive data preprocessing
- 📊 Performance evaluation and visualization
- 🚀 Early stopping to prevent overfitting

## 🖥 Tech Stack

![Python](https://img.shields.io/badge/Python-3.7+-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-2.x-red?logo=keras)
![scikit-learn](https://img.shields.io/badge/scikit--learn-Latest-green?logo=scikit-learn)

## 🛠 Requirements

- 🐍 Python 3.7+
- 💻 TensorFlow
- 🧮 Keras
- 📊 NumPy
- 🐼 Pandas
- 📈 Scikit-learn
- 📊 Matplotlib
- 🎨 Seaborn


## 🧠 Model Architecture
* Input Layer: 4 features
* Sepal length
* Sepal width
* Petal length
* Petal width
* RBF Layer: 10 units, γ = 0.5
* Output Layer: 3 classes
  * 🌼 Setosa
  * 🌷 Versicolor
  * 🌺 Virginica
 
## 📊 Performance Metrics
* 🎯 Accuracy: 91-97%
* 🛑 Early Stopping: Monitored validation loss
* 📊 Batch Size: 4
* 🔄 Maximum Epochs: 300

## 📈 Visualizations Included
* 📊 Feature distribution plots
* 🔥 Correlation heatmap
* 🖼 Pairplots
* 📦 Box plots
* 🔬 Technical Deep Dive
* 🧩 RBF Layer Mechanics


### The Radial Basis Function (RBF) layer processes input data using radial-based activation functions:
* 📍 Centered units
* 🌈 Gaussian radial basis activation
* 🔬 Dynamically learnable center points
### 🧹 Data Preprocessing Techniques
* 📏 Feature scaling with StandardScaler
* 🏷 Label encoding with LabelBinarizer
* 🔀 Train-test data splitting

