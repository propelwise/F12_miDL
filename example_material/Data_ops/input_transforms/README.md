# Dash image processing

https://github.com/plotly/dash-sample-apps/tree/main/apps/dash-image-processing

# Planned use:
Evaluation of monai pre-transforms on sample images, confirmation of transform sequence
https://docs.monai.io/en/latest/transforms.html#vanilla-transforms

# Aim:
help users to visually assess different transforms, different ordering of transforms, and see the result (which is  to be passed as input to DL network)

Need to show dropdown of possible transform operators, and build a sequence by adding (push) one after another using add button, checking output, and popping from the transform list (last in-first out)

## Libraries required:
* monai
https://github.com/Project-MONAI/tutorials/blob/0.6.0/modules/load_medical_images.ipynb
https://github.com/Project-MONAI/tutorials/blob/0.6.0/modules/transforms_demo_2d.ipynb
https://github.com/Project-MONAI/tutorials/blob/0.6.0/modules/3d_image_transforms.ipynb
https://github.com/Project-MONAI/tutorials/blob/0.6.0/modules/inverse_transforms_and_test_time_augmentations.ipynb

* torchIO
https://github.com/Project-MONAI/tutorials/blob/0.6.0/modules/TorchIO_MONAI_PyTorch_Lightning.ipynb

* dash

