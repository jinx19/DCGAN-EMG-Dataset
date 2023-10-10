# DCGAN for Generating Artificial EMG Dataset

This project aims to develop a Deep Convolutional Generative Adversarial Network (DCGAN) to generate an artificial EMG (Electromyography) dataset using an available dataset cited below. The dataset consists of 3000 instances with 2500 attributes. It includes two databases: one with 5 healthy subjects performing six grasps 30 times each, and the other with data from 1 healthy subject performing the same grasps 100 times each for three consecutive days. This ReadMe focuses on the use of Dataset-1.

## Overview

The goal of this project is to use a DCGAN to generate artificial EMG signals based on a pre-existing dataset. The dataset contains EMG signals from five different subjects using two channels. Each activity is repeated 30 times. A consolidated "data" array is created by concatenating EMG signals from various activities.

## Requirements

- Python 3.6 or higher
- NumPy
- Keras
- Pandas
- TensorFlow
- Matplotlib
- Scikit-learn

## Usage

1. Clone this repository.
2. Install the required libraries mentioned above.
3. Pre-process the dataset using MATLAB to generate a training dataset and save it as `train.csv` (Run the `Data_generation.m` file).
4. Train the DCGAN model.
5. Generate artificial EMG signals and save them as `test.csv`.

## Citation

Citation for the dataset used in this project:

C. Sapsanis, G. Georgoulas and A. Tzes, "EMG based classification of basic hand movements based on time-frequency features," 21st Mediterranean Conference on Control and Automation, 2013, pp. 716-722, doi: 10.1109/MED.2013.6608802.

Please consider citing the original dataset source if you use it in your work.

