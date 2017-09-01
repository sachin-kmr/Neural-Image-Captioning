# Image Captioning

This repository contains an implementation of image captioning based on neural network (i.e. CNN + RNN). The model first extracts the image feature by CNN and then generates captions by RNN. CNN is VGG16 and RNN is a standard LSTM .

Normal Sampling and Beam Search were used to predict the caption of images.

Dataset used was <a href="http://nlp.cs.illinois.edu/HockenmaierGroup/Framing_Image_Description/KCCA.html">Flickr8k dataset</a>.

# Dependencies

* Keras 2.0.7
* Theano 0.9.0
* Numpy
* Pandas 0.20.3
* Matplotlib
* Pickle

# References

[1] Deep Visual-Semantic Alignments for Generating Image
Descriptions ( Karpathy et-al, CVPR 2015) 

[2] Oriol Vinyals, Alexander Toshev, Samy Bengio, Dumitru Erhan <a href="https://arxiv.org/abs/1411.4555">Show and Tell: A Neural Image Caption Generator</a>

[3] CS231n: Convolutional Neural Networks for Visual Recognition.
( Instructors : Li Fei Fei, Andrej Karpathy, Justin Johnson)