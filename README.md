# EECS 498-007 / 598-005: Deep Learning for Computer Vision

It's my implementation of the famous course: EECS 498-007 / 598-005: Deep Learning for Computer Vision. 

## Course Website

[The 2022Winter](https://web.eecs.umich.edu/~justincj/teaching/eecs498/WI2022/schedule.html)

## Acknowlegement

During the work, I refer to the work of the 
[Sumxiaa](https://github.com/Sumxiaa/eecs498-007)
and
[1471436961](https://github.com/1471436961/UMich-EECS498-Deep-Learning-for-Computer-Vision)

Thank you for your answers.

## Declaraton
+ The copyright is attributed to the University of Michigan.

+ I completed them with the help of AI.

+ If you think it's helpful, please give me a star(I haven't got one yet, and perhaps you can cheer me up)


# Process

## A1

Completed on 2026.04.14

+ Pytroch Warmup
+ KNN Classifier


## A2

Completed on 2026.04.21

+ SVM Classifier
+ Softmax Classifier
+ Two-layer Net
+ Tuning with visualized website
  + quite interesting


## A3

Completed on 2026.04.26
I utilized AI a lot in this section

+ Fully Connected Networks
  + Linear, ReLU, Linear_ReLU, SGD, SGD with momentum, RMSprop, Adam, Dropout
+ Convolutional Networks
  + Conv, MaxPool, Kaiming Initializer, BatchNorm, SpatialBatchNorm
  + The backward of the CNN is quite complex and I spent a long time to understand it


## A4

Completed on 2026.05.11

+ FCOS
+ Faster R-CNN
  + Unfortunately I only trained a model for 1000 iterations owing to the constraint of the GPU
+ mAP


## A5

Completed on 2026.05.15

+ RNN
+ LSTM
+ Attention-based LSTM
+ Transformer
  + I couldn't find the perfect hyperparameters, so my final model achieved around 70% accuracy.
  + Note: The autograder tests for the Encoder/Decoder blocks and sinusoidal positional encoding seem to have some bugs.
  + I am very excitedbecause I implemented it from scratch with every detail!