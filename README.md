# Crowd Counting 
---
This implementation is written by Hosein Ranjbar

### Introduction
---
This project is an implementation of the crowd counting method proposed in ICCV2021 Oral Presentation

The overall architecture of the P2PNet. Built upon the VGG16, it firstly introduce an upsampling path to obtain fine-grained feature map. Then it exploits two branches to simultaneously predict a set of point proposals and their confidence scores.

## Visualized demos
![](dataset/sample.jpg)

Backbone weights(vgg16) is so big(540MB), It is not uploaded on the Github and you have to download it with the following code
> !wget https://download.pytorch.org/models/vgg16_bn-6c64b313.pth


