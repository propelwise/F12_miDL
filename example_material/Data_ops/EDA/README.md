
## Label prop demo
https://github.com/plotly/dash-sample-apps/tree/main/apps/dash-label-properties

# Planned use:
examine region properties in 2d and 3d

## Libraries required: 
* scikit-image.measure.regionprops_table, 
https://scikit-image.org/docs/dev/auto_examples/segmentation/plot_label.html#sphx-glr-auto-examples-segmentation-plot-label-py

* SimpleITK.LabelShapeStatisticsImageFilter
https://simpleitk.readthedocs.io/en/master/filters.html
http://insightsoftwareconsortium.github.io/SimpleITK-Notebooks/Python_html/35_Segmentation_Shape_Analysis.html


# Aim
* Label analysis for segmentation
provide visual tool to examine training data and labels (overlay, plot properties, distributions of region sizes, shapes)
* bounding box and class analysis for detection
* Input EDA
class level, folder (patient) level, and image level details of data
