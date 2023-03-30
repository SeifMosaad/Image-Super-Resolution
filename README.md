# Image-Super-Resolution
## An Enhanced Deep Residual Network for image super resolution task

We used a model named EDSR which is implementation of the paper "Enhanced Deep Residual Networks for Single Image Super-Resolution" from CVPRW 2017, 2nd NTIRE.

Simply, to run the model you have to follow instructions on this repo [EDSR Repo](https://github.com/sanghyun-son/EDSR-PyTorch) by Sanghyun Son.

We did some minor change on code structure to make it more simple and we only used EDSR model as author provided two models EDSR and MDSR.

Idea behind Performance Recovery Score **PRS** metric is that image enhancement or improving the visual quality of a digital image can be subjective. Saying that one method provides a better-quality image could vary from person to person. So, we want to reach an objective evaluation metric. 
We proposed **PRS** which is an objective measure with the help of deep learning, it’s a classifier as a metric. The higher the classification accuracy "PRS" the better degraded image has been reconstructed to match the original image and the better the reconstructive algorithm.
