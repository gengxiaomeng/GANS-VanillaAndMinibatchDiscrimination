# Vanilla GANS, Minibatch Discrimination - Implementated using PyTorch 

This repository contains my first code in PyTorch: a GAN implemented from scratch (well, not really) and trained to generate MNIST like digits.
Minibatch discrimination, was also implemented to avoid mode-collapse, which is a common phenomenon observed in trained GANS. (Link to paper: https://arxiv.org/abs/1606.03498).

Here is comparison of the generated outputs of GAN, with and without any minibatch discrimination. The networks employed were very simple (only one hidden layer), trained for 20 epochs each with a batch size of 20.
Note that the code for minibatch discrimination is not really optimal at this stage becuase of a for-loop. I am yet to find a way to fix that issue using PyTorch.

![alt text](https://github.com/sanghviyashiitb/GANS-VanillaAndMinibatchDiscrimination/blob/master/Vanilla_GAN_output.png)
![alt text](https://github.com/sanghviyashiitb/GANS-VanillaAndMinibatchDiscrimination/blob/master/MinibatchDiscrimination_GAN_output.png)

</br> (Left) Vanilla GAN outputs (Right) GAN outputs using Minibatch Discrimination Layer
