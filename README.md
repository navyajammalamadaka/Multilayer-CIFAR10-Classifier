# Multilayer-CIFAR10-Classifier

1. Trained a (dense) neural network with three hidden layers with 256, 128, and 64 neurons respectively, all with ReLUactivations 
2. Classified grayscale images from the CIFAR-10 dataset available via torchvision.datasets.CIFAR10.
3. Used torchvision.transforms.Grayscale to convert CIFAR10 images to grayscale.
4. Used a batch size of 64 and SGD optimizer with fixed lr=0.01 and displayed train- and test- loss curves, and report test accuracies of your final model.
