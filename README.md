# ResNet-34 CNN Implementation

Very quick ResNet-34 implementation, a CNN architecture comprised of residual units and skip connections. This architecture showcased the performance boost obtained from training far deeper networks with fewer parameters, whilst avoiding the risk of vanishing gradients.

Bypassing the layers through the use of skip connections allows the signal to be fed to the outputs of layers higher up the stack. Residual units can then focus on learning the residual differences between the inputs and outputs, allowing for easier optimisation.

Architecture proposed in 2015 paper by Kaiming He:

[Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385)