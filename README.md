# Object Localization
Object Localization Model - VOC2012 dataset

### ***Content***

![Objects](https://i.stack.imgur.com/VC1TX.png)

[Visual Object Classes Challenge 2012 (VOC2012)](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/index.html)

The main goal of this challenge is to recognize objects from a number of visual object classes in realistic scenes (i.e. not pre-segmented objects). It is fundamentally a supervised learning problem in that a training set of labelled images is provided. The twenty object classes that have been selected are:

- *Person*: person
- *Animal*: bird, cat, cow, dog, horse, sheep
- *Vehicle*: aeroplane, bicycle, boat, bus, car, motorbike, train
- *Indoor*: bottle, chair, dining table, potted plant, sofa, tv/monitor

**Classification**: For each of the twenty classes, predicting presence/absence of an example of that class in the test image.

**Detection**: Predicting the bounding box and label of each object from the twenty target classes in the test image.
