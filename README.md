# Mango-Disease-Detection-system-using-OpenVino-
I have a Mango Farm of over 200 Trees, these are prone to diseases like powdery mildew, anthracnose, die back, blight, red rust, sooty mould, etc. and once it gets affected to one plant it keeps spreading. 

To avoid this, I have created a Machine Learning Model to detect if a mango plant is unhealthy or not using images of leaves. The inference of this model is Optimized by OpenVino and gaining Inference Speed over 72 times than Normal version.

The training and inference of model is done on Intel Xeon and Ubuntu 18.04. I have used Tensorflow 2.11 for training and OpenVino 20.4 for Inference. When we add images of leaf for input it outputs probability and flag if the leaf is diseased or not
Algorithm; It is a Classification Problem so I have used CNN with Convolution and Max Pooling Layers. 


![2022-11-28 17_04_04-Material Design 1](https://user-images.githubusercontent.com/105711066/204299883-4f3c44ac-f94c-44af-a7b1-2c369d43d96a.png)
![2022-11-28 17_04_33-](https://user-images.githubusercontent.com/105711066/204299899-28044e2f-9f1d-4546-aced-0fead8d4d61d.png)
