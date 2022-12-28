# DCGAN for Generating Artificial EMG Dataset

This project aims to develop a Deep Convolutional Generative Adversarial Network (DCGAN) to generate an artificial EMG dataset using the available dataset cited below. The number of instances and number of attributes of the dataset is 3000 and 2500 respectively. Two different databases are included in the folder, one with 5 healthy subjects (two males and three females) of similar age approximately (20 to 22-year-old) performing six grasps 30 times each, while the other database provided the data of 1 healthy subject(male,22-year-old) performing the six grasps for 100 times each for 3 consecutive days. The movements or the hand grasps that were asked to perform by subjects are Spherical, Tip, Palmar, Lateral, Cylindrical, and Hook. Dataset-1 is only used here.

## Overview

The DCGAN will be used to generate artificial EMG signals by using a pre-existing dataset. The dataset contains EMG signals from five different subjects using two channels. All the activities are repeated 30 times each. A large "data" array is created by concatenating all the EMG signals of different actvities.

## Requirements

- Python 3.6 or higher
- NumPy
- Keras
- Pandas
- TensorFlow
- Matplotlib
- Scikit-learn

## Usage

1. Clone the repository.
2. Install the required libraries.
3. Pre-process the dataset to generate a training dataset using MATLAB and save it as train.csv (Run the Data_generation.m file).
4. Train the DCGAN model.
5. Generate artificial EMG signals and save them as test.csv.

Citation: C. Sapsanis, G. Georgoulas and A. Tzes, "EMG based classification of basic hand movements based on time-frequency features," 21st Mediterranean Conference on Control and Automation, 2013, pp. 716-722, doi: 10.1109/MED.2013.6608802.
