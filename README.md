# Computer Vision Studies

These are results of Udemy course: *Deep Learning: Advanced Computer Vision* [[1]](#1)

The objective of this course is to extend knowledge about image processing with convolutional neural networks. It is also oriented about applying pre-trained, state-of-art CNNs (VGG16, ResNet) to solve specific tasks of object detection, localization, image generation or style transfer

## Features

- simple custom ANN and CNN implementations
- custom ResNet implementation
- using pre-trained ResNet to create class activation map
- using pre-trained VGG16 for style transfer application
- using pre-trained VGG16 for object localization on custom data
- data augmentation using ImageDataGenerator
- preprocessing training dataset to fit the network

## Technologies

- Python
    - sklearn
    - numpy
    - pandas
    - matplotlib, seaborn
- Tensorflow Keras API
- Jupyter Notebook

## Demo

### Style transfer results

Extracted features            | 
:-------------------------:|
![](https://github.com/kwarc-agat/study-computer-vision/blob/main/imgs_style_transfer/persons_outline.png?raw=true) |

Extracted style            |  Styled image
:-------------------------:|:-------------------------:
![](https://github.com/kwarc-agat/study-computer-vision/blob/main/imgs_style_transfer/extracted_style1.png?raw=true)  |  ![](https://github.com/kwarc-agat/study-computer-vision/blob/main/imgs_style_transfer/styled_person1.png?raw=true)
![](https://github.com/kwarc-agat/study-computer-vision/blob/main/imgs_style_transfer/extracted_style2.png?raw=true)  |  ![](https://github.com/kwarc-agat/study-computer-vision/blob/main/imgs_style_transfer/styled_person2.png?raw=true)
![](https://github.com/kwarc-agat/study-computer-vision/blob/main/imgs_style_transfer/extracted_style3.png?raw=true)  |  ![](https://github.com/kwarc-agat/study-computer-vision/blob/main/imgs_style_transfer/styled_person3.png?raw=true)

### Object localization result

![](https://github.com/kwarc-agat/study-computer-vision/blob/main/object_detection.png?raw=true)

### MNIST image generation results (GAN)

<img src="https://github.com/kwarc-agat/study-computer-vision/blob/main/learning_mnist.gif?raw=true" width="500" height="450" />

<img src="https://github.com/kwarc-agat/study-computer-vision/blob/main/gan_mnist.png?raw=true" width="500" height="350">

## Getting started

Browse attached Jupyter Notebooks.

## Misc

<a id="1">[1]</a> Deep Learning: Advanced Computer Vision https://www.udemy.com/course/advanced-computer-vision/