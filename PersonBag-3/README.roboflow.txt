
PersonBag - v3 2024-06-07 11:13am
==============================

This dataset was exported via roboflow.com on June 7, 2024 at 5:46 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 2089 images.
Person-and-bag are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Randomly crop between 0 and 10 percent of the image
* Random rotation of between -15 and +15 degrees
* Random shear of between -13° to +13° horizontally and -11° to +11° vertically
* Random brigthness adjustment of between -10 and +10 percent
* Random exposure adjustment of between -7 and +7 percent


