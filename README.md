# Deep Learning Projects

This repository contains various Deep Learning implementations using **TensorFlow / Keras**, categorized by neural network architectures: **Artificial Neural Networks (ANN)**, **Convolutional Neural Networks (CNN)**, and **Recurrent Neural Networks (RNN)**, along with their respective datasets and saved model artifacts (`.h5`).

---

## 📁 Repository Structure

```
.
├── ANN/
│   ├── mnist-ANN.ipynb             # Classification on MNIST dataset using ANN
│   ├── Ttanic-ANN.ipynb            # Binary classification on Titanic dataset using ANN
│   └── mnist_ann_model.h5          # Saved trained Keras model for MNIST ANN
│
├── CNN/
│   ├── Flowers-CNN.ipynb           # Multi-class image classification on Flowers dataset using CNN
│   ├── mnist-CNN.ipynb             # Digit image classification on MNIST dataset using CNN
│   └── mnist_cnn_model.h5          # Saved trained Keras model for MNIST CNN
│
├── RNN/
│   ├── airline_passengers-RNN.ipynb # Time-series forecasting for Airline Passengers using RNN
│   ├── hosehold_prediction-RNN.ipynb # Time-series forecasting for Household Power Consumption
│   └── SimpleRNN_household_power.h5 # Saved trained Keras SimpleRNN model
│
└── DATASETS/
    ├── Titanic-Dataset.csv         # Structured dataset for Titanic survival prediction
    ├── airline-passengers.csv      # Monthly totals of international airline passengers
    ├── household_power_consumption.csv # Individual household electric power consumption dataset
    └── archive/                    # Archive directory containing additional dataset resources
```

---

## 🧠 Model & Project Details

### 1. Artificial Neural Networks (ANN)
* **`mnist-ANN.ipynb`**: Fully connected dense neural network built to classify handwritten digits (0–9) from the MNIST dataset. Includes data preprocessing, normalization, model architecture setup, training, evaluation, and model saving (`mnist_ann_model.h5`).
* **`Ttanic-ANN.ipynb`**: Dense network trained on structured tabular data (`Titanic-Dataset.csv`) to predict passenger survival outcomes based on demographic and ticket attributes.

### 2. Convolutional Neural Networks (CNN)
* **`mnist-CNN.ipynb`**: 2D Convolutional neural network leveraging Conv2D, MaxPooling, and Flatten layers to extract spatial features from MNIST digit images for higher classification accuracy (`mnist_cnn_model.h5`).
* **`Flowers-CNN.ipynb`**: Image classification model trained to categorize flower images into distinct visual categories.

### 3. Recurrent Neural Networks (RNN)
* **`airline_passengers-RNN.ipynb`**: Time-series prediction model using Recurrent Neural Networks (SimpleRNN / LSTM) to forecast future passenger demand using historical time-series sequences (`airline-passengers.csv`).
* **`hosehold_prediction-RNN.ipynb`**: Sequence modeling and multi-step time-series forecasting on household power consumption data (`household_power_consumption.csv`, model saved as `SimpleRNN_household_power.h5`).

---

## ⚙️ Requirements & Installation

To run the Jupyter Notebooks in this repository, ensure you have Python 3.8+ installed along with the following libraries:

```bash
pip install tensorflow keras numpy pandas matplotlib scikit-learn jupyter
```

---

## 🚀 How to Run

1. Clone or download this repository:
   ```bash
   git clone https://github.com/Shaipratt51/DEEP-LEARNING
   cd DEEP_LEARNING
   ```
2. Launch Jupyter Notebook or JupyterLab:
   ```bash
   jupyter notebook
   ```
3. Open any `.ipynb` notebook inside `ANN/`, `CNN/`, or `RNN/` and execute the cells.
