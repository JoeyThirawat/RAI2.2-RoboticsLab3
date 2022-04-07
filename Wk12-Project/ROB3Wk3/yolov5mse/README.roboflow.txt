
RoboProject01 - v1 2022-04-06 7:00pm
==============================

This dataset was exported via roboflow.ai on April 6, 2022 at 12:01 PM GMT

It includes 130 images.
Mouse are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Random rotation of between -15 and +15 degrees
* Random shear of between -10° to +10° horizontally and -20° to +20° vertically


