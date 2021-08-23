# Segmentation
## segmentation baseline code
https://github.com/Project-MONAI/tutorials/blob/0.6.0/3d_segmentation/torch/unet_training_dict.py
https://github.com/Project-MONAI/tutorials/blob/0.6.0/3d_segmentation/torch/unet_evaluation_dict.py
https://github.com/Project-MONAI/tutorials/blob/0.6.0/3d_segmentation/torch/unet_inference_dict.py

## Metrics for segmentation

https://scikit-image.org/docs/dev/auto_examples/segmentation/plot_metrics.
html#sphx-glr-auto-examples-segmentation-plot-metrics-py

http://insightsoftwareconsortium.github.io/SimpleITK-Notebooks/Python_html/34_Segmentation_Evaluation.html

# Classification
## classification baseline code
https://github.com/Project-MONAI/tutorials/blob/0.6.0/modules/interpretability/covid_classification.ipynb

## sklearn classification report, plot_confusion_matrix
https://scikit-learn.org/stable/modules/model_evaluation.html

# Aim:
__Segmentation__: provide per-label, per-image and per-batch trend lines (epoch by epoch) for Dice metric in validation set

__classification__: Provide per-image, per-batch classification label trend (epoch by epoch) in validation set 

Help to isolate or group images based on performance, and visually inspecting what is common among images which are performing well (or poorly, or oscillating, etc)

Provide data for judging if sample balancing, or data augmentation, or folded validation, or model ensembling, or ... can improve results


## Libraries required:
* monai 0.6.0
* scikit-image
* numpy,scipy
