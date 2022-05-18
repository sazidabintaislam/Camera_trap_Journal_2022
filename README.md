# Small Animal Species Recognition with Deep Convolutional Neural Network from Ecological Camera Trap Image.

#### This repository contains the experiment files of masters thesis research work which is, wild animal species recognition (snake, lizard and toad) by image classification using computer vision algorithms and machine learning techniques. The goal is to train and validate a convolutional neural network (CNN) architecture that will classify three herpetofauna species: snake, lizard, and toad from the camera trap samples.

#### The proposed solution offers two self-trained deep convolutional neural network (DCNN) classification algorithms CNN-1 and CNN-2, to solve binary and multiclass problem. The machine learning block of both architectures is same for the CNN-1 and CNN-2, while CNN-2 has been incorporated with several data augmentation processes such as rotation, zoom, flip, and shift to the existing samples during the training period.

#### The initial experiment implies building a flexible binary and multiclass CNN architecture with labeled images accumulated from several online sources. Once the baseline model is formulated and tested with satisfactory accuracy, new camera trap imagery data is executed to the model for recognition purpose. All three species have classified individually regarding background samples to distinguish the presence of target species in a camera trap dataset. The performance is evaluated based on the classification accuracy within their group using two separate sets of validation and testing data. In the end, both models have tested to predict the category of a new example to compare the models' generalization ability with a challenging camera trap data.
## Dataset:
Online dataset: Image samples collecetd from online database (the dataset samples are publicly available on prior permission)
Camera trap dataset: Field dataset collected from Texas (the dataset samples are not publicly available.).
## Models:
CNN-1: without implementing augmentation
CNN-2: with augmentation
## Experiments:
Binary
Multiclass
