# F12_miDL
Data exploration of medical imaging DL input data, (visual subsetting, data grouping, balancing), + EDA of DL output (what-if, epoch-by epoch performance change) in pure python

This will be the inspect (F12) tool for medical image deep learning.

https://www.upwork.com/jobs/~01c7a2469372ee3c59

Project toolset: pytorch (1.8.1), monai (0.6), plotly dash (for UI), sklearn (for EDA), scikit-image (2d image analysis), simpleitk (3d image analysis)

The initial development effort would be 3 months, and carried out (and continued) here. Goal is to prototype a data science utility for analyzing the input (EDA) and output (what-if) of deep learning applied to medical image classification, segmentation and object detection tasks.

We will demonstrate the project outcomes by plugging in standard tutorial code from monai, applied on datasets from grand-challenge.org and ongoing kaggle challenges
1. https://www.kaggle.com/c/rsna-miccai-brain-tumor-radiogenomic-classification
2. https://qubiq21.grand-challenge.org/
