# Emg-hand-prosthesis
Educational project on classifying synthetic EMG signals and simulating prosthetic hand control using machine learning.
EMG-Prosthetic-Control

Educational project on classifying synthetic EMG signals and simulating prosthetic hand control using machine learning.

Overview

This project demonstrates a mini pipeline for AI in rehabilitation robotics:

Generate synthetic EMG signals for three classes (Rest, Fist, Open Hand).

Extract simple features (Mean, RMS, Variance).

Train a Random Forest classifier.

Evaluate the model using accuracy and confusion matrix.

Map predicted commands to a simple proportional controller that simulates a prosthetic hand angle.

Results

The model achieved 100% accuracy on synthetic data.

Commands (0 = Rest, 1 = Fist, 2 = Open) were successfully mapped to prosthetic hand angles (0°–90°).

Example visualization shows how angles follow predicted commands over time.

Requirements

Python 3.x

Libraries: numpy, pandas, scikit-learn, matplotlib

How to Run

Clone the repository:

git clone https://github.com/Rehabilitation_AI/emg-prosthetic-control.git
cd emg-prosthetic-control


Open the Jupyter Notebook:

jupyter notebook emg_prosthetic_control.ipynb


Run all cells to generate data, train the model, and simulate prosthetic control.

Future Work:

.Test with real EMG data

.Add more advanced models (e.g., LSTM, CNN)

.Integrate with real-time control for prosthetic devices
