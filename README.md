This code was used to generate the output for the CGIAR Crop Yield Prediction Challenge (https://zindi.africa/competitions/cgiar-crop-yield-prediction-challenge).

First, for a given field, the raw satellite image data set was converted into a C x N x P matrix of histograms (where C denotes the number of channels, N denotes the number of histogram bins, and P denotes the number of time points) in a manner similar to that described by You et al. (Proc. Thirty-First AAAI Conference on Artificial Intelligence, 2017, Pp 4559–4565). Next, a CNN was developed to estimate the crop yield using the 3D histograms as input.


