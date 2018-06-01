# Image_Classification
## 1.Convolution
![avatar](https://developers.google.cn/machine-learning/practica/image-classification/images/convolution_overview.gif)

## 2.ReLU
The ReLU function, F(x)=max(0,x), returns x for all values of x > 0, and returns 0 for all values of x ≤ 0.

## 3.Pooling
Size of the max-pooling filter (typically 2x2 pixels)
Stride: the distance, in pixels, separating each extracted tile. Unlike with convolution, where filters slide over the feature map pixel by pixel, in max pooling, the stride determines the locations where each tile is extracted. For a 2x2 filter, a stride of 2 specifies that the max pooling operation will extract all nonoverlapping 2x2 tiles from the feature map (see Figure 5).
![avatar](https://developers.google.cn/machine-learning/practica/image-classification/images/maxpool_animation.gif)

## 4.Fully Connected Layers
![avatar](https://developers.google.cn/machine-learning/practica/image-classification/images/cnn_architecture.svg)
