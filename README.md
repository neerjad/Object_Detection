# Object_Detection
Implementing an algorithm for automatic caption generation of images in Pytorch.

**Single Shot Detection** is used to extract features from images which will be passed to LSTMs for caption generation.
The SSD implementation is inspired from Jeremy Howard's Deep Learning Part 2.

1. single_object_pascal.ipynb: This code just detects the largest object in every image along with its bounding box coordinates.

2. multiple_objects.ipynb: This code detects multiple objects in an image along with their locations in the image.

3. basic_char_level_rnn.ipynb: Understanding how rnns work by building a simple name generator.

4. coco_preprocessing.ipynb: Preproccessing the coco dataset using COCO API.

5. word_level_rnn.ipynb: Extending char level rnn to generate work. Still in progress.
