# Comparison Validation

The **comparision.ipynb** notebook includes a comparison validation of MEGnet between BrainStorm and MNE, as well as consistency verification between ONNX and Keras.

## BrainStorm Features

The `bt_features` directory contains topomap and time series data from BrainStorm. The names of the PNG files correspond to the IC numbers, and the `.mat` file is the ICA data from BrainStorm. The array within the file is of shape (nComponent x nTime), and the corresponding key is `'Values'`.

## Feature Extraction and Classification

The scripts **features.py** and **label_component.py** contain the code for feature extraction and classification of ICs in MNE, respectively.
