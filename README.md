# SOC 2021 - A Deep Dive into CNNs


## Checkpoints 

### Checkpoint 1
The first part of the learning project was to complete two courses on coursera [link](https://www.coursera.org/specializations/deep-learning?utm_source=gg&utm_medium=sem&utm_campaign=17-DeepLearning-IN&utm_content=17-DeepLearning-IN&campaignid=6495527979&adgroupid=119719595459&device=c&keyword=&matchtype=b&network=g&devicemodel=&adpostion=&creativeid=507236116448&hide_mobile_promo&gclid=CjwKCAjwos-HBhB3EiwAe4xM9wJh8ZUqpmrSipVW4uUTeNcAXttmBicr4cLFkGWVhkd3EvCGCZiPJhoCQ0MQAvD_BwE).

Over here assignments have been attached.

The key takeaway here was to learn about implementing NeuralNetworks in Python, interesting things like numpy vectorization and other optimization were introduced.

Things Learned In Brief:
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

AlexNet was implemented in reference to the [paper](https://papers.nips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf) and [article](https://medium.com/swlh/scratch-to-sota-build-famous-classification-nets-2-alexnet-vgg-50a4f55f7f56) .

The rest all were implemented from this repo : [link](https://github.com/bentrevett/pytorch-image-classification)


The models were trained on Cifar100 and FashionMNIST.

Observations for the FashionMNIST Dataset:
1. Due to poor resources it was observed that AlexNet, VGGNet perform very well and train very quickly.
2. AlexNet showed very high accuracy on test_data.

Transfer learning could not be implemented on FashionMNIST as it was having grayscale images, whereas the pretrained models are trained for coloured images.

Observations for the Cifar100 Dataset:

Yet following points can be mentioned:
1. AlexNet did not perform very well.
2. VGGNet and ResNet showed very good results > 45 % Accuracies.


> Google LeNet : The implementation similar to https://github.com/bentrevett/pytorch-image-classification/blob/master/2_lenet.ipynb performed very poorly, it achieved accuracy of < 15 % for both FashionMNIST and CIFAR100. 


Please take this into consideration that to lack of resources complete training could not be done of the model , hence it is possible the certain models performed very poorly.


### Checkpoint 4 
 Simple transfer learning is implemented using pretrained VGGNet, ResNet on CIFAR100, achieving accuracy in range of 48 - 58 %.
