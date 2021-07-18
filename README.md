# WNCC SOC 2021 - Assignment


## Checkpoints 

### Checkpoint 1
The first part of the learning project was to complete two courses on coursera [link](https://www.coursera.org/specializations/deep-learning?utm_source=gg&utm_medium=sem&utm_campaign=17-DeepLearning-IN&utm_content=17-DeepLearning-IN&campaignid=6495527979&adgroupid=119719595459&device=c&keyword=&matchtype=b&network=g&devicemodel=&adpostion=&creativeid=507236116448&hide_mobile_promo&gclid=CjwKCAjwos-HBhB3EiwAe4xM9wJh8ZUqpmrSipVW4uUTeNcAXttmBicr4cLFkGWVhkd3EvCGCZiPJhoCQ0MQAvD_BwE).

Over here assignments have been attached.

The key takeaway here was to learn about implementing NeuralNetworks in Python, interesting things like numpy vectorization and other optimization were introduced.

#### Things Learned In Breif
1. What are Neural Networks ? 
2. Backpropogation and Feed Forward and other process associated.
3. Numpy vectorization optimizations and tricks.
4. Gradient Descend and different Optimizer.
5. Hyperparameter tuning intro.


### Checkpoint 2
To test all theory and application of the coursera course a simple assignment was to implement, a simple MNIST model in PyTorch, to learn the basics of Pytorch.

A simple PyTorch network has been implemented on MNIST given sufficient accuracy.

### Checkpoint 3 
Following models are implemented and trained : 
1. AlexNet
2. VGGNet
3. ResNet
4. GoogLeNet



> Due to resource constrains models have been only partially trained 2-5 epochs.

Yet following points can be mentioned:
1. VGGNet trained very fast compared to AlexNet.
2. Performance of AlexNet however was better on training set , VGG being simple probably overfitted.

### Checkpoint 4 
 Simple transfer learning is implemented using pretrained VGGNet on CIFAR100, achieving accuracy of 58 %.
