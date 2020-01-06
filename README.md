# MobileNetGray
This repo is for using MobileNet on Gray scale image

### Goal

Gray scale images are widely used in differernt research area.


### Method

#### Mobile Net and pretrained 

pretrained parameter is donwload from [here](https://pytorch.org/hub/pytorch_vision_mobilenet_v2/)


#### CIFAR 100 and gray scale


### result

|training set|   Method  | accuracy  | 
|---          | ----      | ----  |
|RGB       |  pre-trained     | 0.3%  |
|RGB       | fine-tuning FC layer    | 61% |
|RGB       | fine-tuning all network | 80.6% |
|Gray (3)  |  pre-trained     | 1%  |
|Gray (3)  |  fine-tuning FC layer     | 46%  |
|Gray (3)  | fine-tuning all network | 71.5% |
|Gray (1)  |  fine-tuning FC layer     | 43%  |
|Gray (1)  | fine-tuning all network | 71% |
