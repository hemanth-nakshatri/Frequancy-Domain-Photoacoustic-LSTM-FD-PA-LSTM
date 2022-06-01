# Frequancy-Domain-Optoacoustic-LSTM-FD-OA-LSTM-
This is a novel Deep learning approach for the frequency domain photoacoustic reconstruction using LSTM.

## Parameters
Set the path and other parameters in the beginning of the _FD-OA LSTM.ipynb_ file.

## Step 1. Generate forward model dataset for training
Generate the forward model dataset for training using the _Generate Data Final.ipynb_ by setting correct path for source and output. To be done separately for 150 degree FOV and 300 degree FOV.

## Step 2. Train the model
Train the model using _FD-OA LSTM.ipynb_ after setting the appropriate parameters. Both the models are trained for data with 40dB SNR in the data and tested with data containg 20dB, 30dB and 40dB SNR.

## Step 3. Test the performance
Validate the model using the test data and also compare PSNR and SSIM.
