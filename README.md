# Transfer-Learning---PreTrained-Network
Building a Convolutional Neural Network from scratch and then applying Transfer Learning to a Pretrained network and later on applying Data Augmentation to the Pretrained Network.

### Steps Involved

`1.` Building a small CNN from scratch with two versions. One version has dropout layers but the other doesn't.

`2.` Train both versions of the CNN on the [CalTech-101](https://www.tensorflow.org/datasets/catalog/caltech101) dataset and determine the accuracy on the test data for each versio of the network.

`3.` Load a pre-trained network (ResNet50V2) i.e (keras.applications.ResNet50V2).

`4.` Adapt the model to the Caltech-101 dataset and retrain.

`5.` For the first set of retraining, keep all the layers frozen except the last one.

`6.` Then, retrain again, unfreezing one extra layer. After that, compare the accuracies of these two retrained models with each other and also with the CNN's built from scratch.

`7.` Retain the ResNet50V2 model again, after applying some Data Augmentation techniques and compare the results and accuracies.
