# Introduction
This document discuss implementing convolutional neural network to predict the MPW and MPD based on PBF melt pool images.

# Dataset
The model was developed and trained using Pytorch open source framework. While the uploaded code is ran in Google's Colaboratory to utilize its GPU, the data that the model was trained on is additionally uploaded so that you can run the code yourself in whatever coding environment you intend to experiment. The data consists of 1) melt pool images and 2) exact melt pool width and depth values of the images computed algorithmically by LiveLink for MATLAB.
1) [Image data](https://drive.google.com/file/d/1vDWtT3mJHI0hRGruFP1zBzh1P9vbtCs9/view?usp=sharing)
2) [Melt Pool Labels](https://github.com/Shim-John/MPW_MPD_Image-Prediction/blob/9fdc99f0b689ed76aad6e6313be7ffbda695a6ae/Melt%20Pool%20Labels.zip)

# Models
1) [MPW Model](https://github.com/Shim-John/Meltpool_Image-Prediction/blob/d49a3088505207dbddd002db22664df4e0136b8c/K_Fold_MPW.ipynb)
2) [MPD Model](https://github.com/Shim-John/Meltpool_Image-Prediction/blob/e5614b9d0bf0e0edcf3ba9b4886350c4864a56af/K_Fold_MPD.ipynb)
