# Classifier
 - Deep CNN trained on Cross-Entropy Loss to classify images in the AddNIST dataset
 - Aim: make the most accurate classifier possible with under 100,000 parameters in 10,000 training steps
 - Utilises Squeeze-and-Excitation and Inverted Residual blocks
 - Achieved 84.95% test accuracy with 86,692 parameters in 10,000 training steps

# Generator
 - Designed and trained a DCGAN on binary cross-entropy loss to generate realistic, diverse images
 - Aim: by using the CIFAR-100 dataset, make the most realistic and diverse image generator possible with under 1 million parameters in under 50,000 optimisation steps
 - Utilises learning rate schedulers that decrease the learning rate throughout training
 - Achieved FID score of 44.46 with a mean LPIPS score of 0.686 ± 0.009 with only 967,072 parameters in 50,000 optimisation steps.
