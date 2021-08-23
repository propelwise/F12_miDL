# F12_miDL
Data exploration of medical imaging DL input data, (visual subsetting, data grouping, balancing), + EDA of DL output (what-if, epoch-by epoch performance change) in pure python

This will be the inspect (F12) tool for medical image deep learning.

# Aim
Provide data science tools building upon pytorch, Monai, sklearn, dash
Pure python, UI implemented via dash.

# Modules
## Data ops: 
exploration of input data, grouping, subsetting, planning for training dataset

__Input__: 
csv file in the format (image_path, label_path) - segmentation or 
    (image_path, label) - classification or
    (image_path, coco_json_path) - object detection
    
__tools__:
1. EDA of labels, regions
1. input transform checking


## Process Analysis: 
Help to isolate or group images based on performance, and visually inspecting what is common among images which are performing well (or poorly, or oscillating, etc)

Provide data for judging if sample balancing, or data augmentation, or folded validation, or model ensembling, or ... can improve results

