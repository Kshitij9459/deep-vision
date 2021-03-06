# Deep Learning in Computer Vision (deep-vision)

[PyTorch](https://github.com/pytorch/pytorch) / [Tensorflow](https://github.com/tensorflow/tensorflow) implementations of classic deep neural networks and training scripts for computer vision tasks. This is used to ease the learning curve for new DL practitioners by two principles: 1) Keep the coding style consistent accross all networks 2) Focus on the code readability and avoid obscure tricks. If you think my work is helpful, please ⭐star⭐ this repo. If you have any questions regarding the code, feel free create an issue.

The directory is categorized by model architecture, then further by framework. Some pretrained models, Jupyter notebook visuliazation script, and training logs are also provided for your reference.

## Image Classification

- AlexNet
    - PyTorch
        - AlexNet V1
        - AlexNet V2
    - TensorFlow
        - AlexNet V2
- VGG
    - PyTorch
        - VGG-16/19
- Inception (GoogLeNet)
    - PyTorch
        - Inception V1
        - Inception V3
- ResNet
    - PyTorch
        - ResNet-34/50/152 V1
    - TensorFlow
        - ResNet-50/152 V1
        - ResNet-50 V2
- MobileNet
    - PyTorch
        - MobileNet V1 1.0
- LeNet
    - PyTorch
        - LeNet-5
    - TensorFlow
        - LeNet-5

## Object Detection

- YOLO
    - TensorFlow
        - YOLO V3

## Generative Adversarial Network

- DCGAN
    - TensorFlow
- CycleGAN 
    - TensorFlow

## Pose Estimation

- Stacked Hourglass
    - TensorFlow
        - Hourglass-104

## Disclaimer

- This repo is mainly for study purpose. Hence I write the code in a readable and understandable way, but may not be scalable and reusable. I've also added comments and referrence for those catches I ran into during replication.
- I'm not a researcher so don't have that much of time to tune the training and achieve the best benchmark. If you are looking for pre-trained models for transfer learning, there're some good ones from [PyTorch torchvision](https://pytorch.org/docs/stable/torchvision/models.html) or [TensorFlow slim](https://github.com/tensorflow/models/tree/master/research/slim).

## Acknowledgement

Without the following resources I wouldn't be able to finish this project:

- [Deep Learning Specialization](https://www.deeplearning.ai/deep-learning-specialization/) by deeplearning.ai and Coursera
- [Computer Vision Nanodegree](https://www.udacity.com/course/computer-vision-nanodegree--nd891) by Udacity
- [Hands-On Machine Learning with Scikit-Learn and TensorFlow](https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1491962291?keywords=hands+on+machine+learning&qid=1547709501&s=Books&sr=1-3&ref=sr_1_3) by Aurélien Géron