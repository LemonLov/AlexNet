# AlexNet
This is an implement of AlexNet base on [kratzert's work](https://github.com/kratzert/finetune_alexnet_with_tensorflow).
It can apply to others classification tasks through modifying the last fully-connected layer. In the same time, you can choose the network's layer you want to train. The pre-trained weights of AlexNet can be found in [here](http://www.cs.toronto.edu/~guerzhoy/tf_alexnet/) and another dataset can be found in [here](https://pan.baidu.com/s/1Drhq1Xrs5zTju690DHvf_Q) whose extraction code is "lvhc". You need to pull them under the home directory when you need to utilize them.

The experiment environment is as follows:
- tensorflow=1.12.0
- pyhton=3.6.7
- numpy=1.16.2
