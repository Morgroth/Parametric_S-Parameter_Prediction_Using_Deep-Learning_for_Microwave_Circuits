This repository contains the code for the manuscript "Parametric S-Parameter Prediction Using Deep Learning".
URL : https://ieeexplore.ieee.org/document/10754126
Citation : V. Bansal, L. Feng, V. d. la Rubia and P. Benner, “Parametric S-Parameter Prediction Using Deep Learning,”  2024 IEEE 33rd Conference on Electrical Performance of Electronic Packaging and Systems (EPEPS), Toronto, ON, Canada, 2024, pp. 1-3, doi: 10.1109/EPEPS61853.2024.10754126.

The dependencies required for running the code are mentioned in the "requirements.txt" file.

The main script is "Parametric_S_Parameter_Prediction_Using_Deep_Learning.ipynb". 

This Jupyter notebook contains the code for loading the data, training the CAE + DFNN (our proposed network) and the STCNN (Spatio-Temporal Convolutional Neural Network, used for comparison) and plots comparing the results of these models.

The data is in the file "s_data.mat"

Files "encoder.keras" and "decoder.keras" contain the architectures for the two subnetworks of the CAE and "autoencoder.h5" contains the weights for the combined CAE.

File "STCNN_Solenoid.pth.textClipping" contains the weights for the STCNN.

Files "dfnn.keras" and "dfnn.h5" contain the architecture and weights for the DFNN resp.


