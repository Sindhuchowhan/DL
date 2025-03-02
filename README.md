# DL
To achieve higher accuracy on the EMNIST dataset using a fully connected neural network, the following hyperparameter choices are recommended:
Epochs: Training for 10 epochs strikes a balance between performance and overfitting.

Weight Initialization: The Xavier (Glorot) initialization method helps in stabilizing gradients and improves convergence.

Activation Function: The ReLU activation function is recommended for all hidden layers.

Learning Rate: For Adam and RMSprop, a learning rate of 1e-3 (0.001) provides stable convergence. 

Hidden Layers: A 4-5 layer deep network offers a good balance between expressiveness and generalization.

Weight Decay (L2 Regularization): Setting the L2 regularization (weight decay) to 0.0005 helps prevent overfitting while maintaining model flexibility.

Batch Size: A batch size of 64 is optimal, as it balances training speed and generalization. 

Optimizer Choice: The Adam optimizer is the most effective for adaptive learning.
