
Weapon Detection - v5 drake
==============================

This dataset was exported via roboflow.com on August 12, 2022 at 3:07 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

It includes 1671 images.
Weapons are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 300x300 (Fit within)
* Grayscale (CRT phosphor)
* Auto-contrast via histogram equalization

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Random rotation of between -26 and +26 degrees
* Random brigthness adjustment of between -51 and +51 percent
* Random Gaussian blur of between 0 and 3 pixels
* Salt and pepper noise was applied to 25 percent of pixels


