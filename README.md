# ml-lab

## Contents

### [bigram model](./bigram_model/bigram_model.ipynb)

A bigram language model. This implementation shows how to create a simple character-level language model that can generate new words similar to examples it has seen.

### [micrograd](./micrograd/micrograd.ipynb)

An implementation of a small autograd engine, inspired by Andrej Karpathy's micrograd.
This notebook demonstrates building neural networks from scratch with automatic differentiation.

### [neural_probabilistic_language_model](./neural_probabilistic_language_model/neural_probabilistic_language_model.ipynb)

Implementation of the Neural Probabilistic Language Model as introduced by Bengio et al. This notebook explores the foundations of neural language modeling.

### [batch_norm](./batch_norm/batch_norm.ipynb)

Experiments with Batch Normalization in neural networks.
This notebook explores how batch normalization affects training dynamics, convergence speed, and overall performance by comparing models with and without this technique.

### [optimizers](./optimizers/optimizers.ipynb)
Visualization and analysis of optimization algorithms including SGD, Momentum, and Adam.

### [convolution](./convolution/)
A series of notebooks exploring convolutional neural networks:
- [convolution_fundamentals](./convolution/convolution_fundamentals.ipynb): Understanding the mathematics and intuition behind convolution operations.
- [mnist_linear](./convolution/mnist_linear.ipynb): Implementation of linear and MLP models on the MNIST dataset.
- [mnist_cnn](./convolution/mnist_cnn.ipynb): Implementation of CNNs on MNIST, demonstrating how convolutions improve performance.
- [fashion_mnist](./convolution/fashion_mnist.ipynb): Implementation of CNN architectures on the Fashion-MNIST dataset, demonstrating performance on a more complex image classification task with clothing items.
- [cat_and_dog](./convolution/cat_and_dog.ipynb): Comparative implementation of cat vs. dog image classification using three approaches: PyTorch, Keras, and an AlexNet architecture in PyTorch, showcasing framework differences and architecture choices.
- [cifar_10](./convolution/cifar_10.ipynb): Comparison of advanced CNN architectures (AlexNet, ResNet, DenseNet) on the CIFAR-10 dataset, showcasing the evolution and improvements in convolutional network design
- [german_traffic_sign](./convolution/%20german_traffic_sign.ipynb)

### [object-detection](./object_detection/)
Exploration of object detection techniques. This directory contains implementations and experiments, demonstrating real-time object detection capabilities and applications.
- [car-detection](./object_detection/car_object_detection.ipynb): Implementation of YOLO for detecting cars in images and video.

### [npl](./nlp/)
Natural language processing
- [text_classification](./nlp/text_classification.ipynb): Implementation of Text classification tasks with multiple ML algorithms
- [token_classification](./nlp/token_classification.ipynb): Implementation of Token classification (Named entity recognition)