# Train an LSTM Model for Time-Series Prediction

An assignment focusing on training a Long Short-Term Memory (LSTM) neural network to perform time-series forecasting.

## Project Overview

This notebook demonstrates how an LSTM network learns temporal dependencies by predicting the **next value of a sine wave** based on the previous 20 sequence values. A sine wave offers a simple, repeating pattern ideal for demonstrating time-series principles without requiring external dataset downloads.

### Key Concepts

* **Why LSTMs?** Standard feed-forward neural networks lack memory, treating each input independently. LSTMs contain internal memory cells designed to pass information across time steps, which is critical when the sequence order matters.
* **Self-Contained Dataset:** A 1,000-point sine wave is generated dynamically using NumPy, making the notebook lightweight and self-contained.

---

## Workflow Steps

### Step 1: Import Libraries
Set up the environment using standard Python scientific and machine learning packages:
* **NumPy** for numerical manipulations and dataset generation
* **Matplotlib** for visualization of the time-series sequence and model predictions
* **TensorFlow / Keras** for constructing and training the LSTM network using `Sequential`, `LSTM`, and `Dense` layers

### Step 2: Dataset Generation
Generate 1,000 evenly spaced points of $y = \sin(x)$ with NumPy to act as the raw input data.

---

## Requirements

* Python 3.x
* TensorFlow 2.x
* NumPy
* Matplotlib
