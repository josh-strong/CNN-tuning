# CNN-tuning

This notebook includes tuning hyperparameters of a convolutional neural network to optimise for minimal cross-entropy loss. In doing so, 9 model variants are developed with increasing generalisation performance. The final model involves 3x3 filters with 99.44% validation accuracy, 99.18% testing accuracy and 100% training accuracy.

The code itself is written in Julia, with a hack by Pontus Stenetorp (https://pontus.stenetorp.se/) allowing for Julia support in google colab notebooks.
