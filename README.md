# Foundations of Convolutional Neural Networks, deeplearning.ai coursera course

## Week 1: Foundations of Convolutional Neural Networks

Introduction to Convolution, pooling and paddnig.

- Familiar formula: conv layer output size = (n + 2*p - k)/s + 1

- Number of params in ten 3x3x3 filtres: (3x3x3 + 1[bias]) x 10 = 280

**Assignment 1:** Implement conv layer in numpy (forward/backward)

**Assignment 2:** Intro. to TensorFlow

## Week 2: Deep convolutional models: case studies

ResNet
- Residual block
- Why it works? Skip-connection make NNs easy to learn. Prevent gradient vanishing.

Inception
- Bottleneck layer: Apply 1x1 conv to shrink channel size 
- Concatenate output of different conv routes

**Assignment 1:** Intro. to Keras
- `Input(shape=...) `=> `[Conv2D/BN/ReLU]` x N => `model=Model(input, output)` => `mdoel.compile(...)` => `model.fit(...)`

**Assignmnet 2:** ResNet50
- `convolution_block`: A block that reduces dimnension by 2 using stride2 Conv2D 
- `identity_block`: Con2D/BN/ReLU => Conv2D/BN => Add => ReLU
  
## Week 3: Object detection

## Week 4: Special applications: Face recognition & Neural style transfer
