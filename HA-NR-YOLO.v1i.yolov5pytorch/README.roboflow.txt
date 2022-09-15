
HA-NR-YOLO - v1 2022-09-07 3:31pm
==============================

This dataset was exported via roboflow.com on September 7, 2022 at 7:32 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

It includes 120 images.
OBJECTS are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* Random rotation of between -15 and +15 degrees

The following transformations were applied to the bounding boxes of each image:
* Random Gaussian blur of between 0 and 10 pixels
* Salt and pepper noise was applied to 10 percent of pixels


