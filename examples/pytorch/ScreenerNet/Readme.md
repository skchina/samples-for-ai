This is a reimplementation of [ScreenerNet: Learning Self-Paced Curriculum for Deep Neural Networks](https://arxiv.org/abs/1801.00904)

[简体中文](/zh-hans/examples/pytorch/PyTorchExamples/ScreenerNet/Readme.md)

# prerequisites
0.4.0=>pytorch>=0.3.0

## extra dataset
If you want to train on pascal voc2012 dataset, make sure that you have download it and put it in PWD/VOC2012
download mirror: https://pjreddie.com/projects/pascal-voc-dataset-mirror/

Else, MNIST and CIFAR10 can automatically be download by pytorch.

# how to run
please type
```
python snet.py -h 
```
to see all train and test options.

For example:
```
python snet.py train mnist
python snet.py test mnist --modelname=your_model_name 
```
