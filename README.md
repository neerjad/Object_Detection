# Object_Detection
Implementing an algorithm for automatic caption generation of images in Pytorch.

**Single Shot Detection** is used to extract features from images which will be passed to LSTMs for caption generation.
The SSD implementation is inspired from Jeremy Howard's Deep Learning Part 2.

1. single_object_pascal.ipynb: This code just detects the largest object in every image along with its bounding box coordinates.
2. multiple_objects.ipynb: This code detects multiple objects in an image along with their locations in the image.
