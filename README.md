# Squeeze-and-Excitation-Network-from-scratch

[SEBlock]: ./Images/SE_Block.png "SE Block"
[SER]: ./Images/SE_ResNet50.png "SE-ResNet"
[output]: ./Images/Output.png "Output"


Part 2 of "From Scratch" Series. You can view the Part 1 here - [Inception v3 from scratch](https://github.com/ambareesh-ravi/Inception-v3-from-scratch). 



This project is a Tensorflow 2.0 implementation of Squeeze and Excitation ResNet50 network from scratch.


![Squeeze and Excitation Block][SEBlock]


```
Squeeze and Excitation Network (SENet) introduces a building block for CNNs 
that improves channel interdependencies at almost no computational cost.
```

Generally, a Convolutional Neural Network weights each of its channels(filters) equally when creating new feature maps. SENets introduces the concept of adding parameters to each channel of a conv block so that network can adaptively adjust the weighting of each feature map.

## Model

SENets blocks can be added to any existing CNN models at almost no cost and helps in achieving more accuracy.

![SENet blocks in Inception and ResNet50][SER]

## Output

![Prediction on ImageNet Dataset][output]

## Citation

      @inproceedings{hu2018senet,
        title={Squeeze-and-Excitation Networks},
        author={Jie Hu and Li Shen and Gang Sun},
        journal={IEEE Conference on Computer Vision and Pattern Recognition},
        year={2018}
      }
