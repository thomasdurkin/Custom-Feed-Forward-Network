# Custom Feed Forward Neural Network
An 3 layer multilayer perceptron network built from scratch using PyTorch. Network was trained to distinguish between pictures of cats and dogs. ReLU activation function was used for the first two layers and sigmoid was used for the last. Objection function used was Binary Cross-Entropy Loss. Final results presented the accuracy for the cat class as 72.7% and dog class as 48.4%.
Since a feed forward network is not an optimal solution for this problem a CNN was also created resulting in accuracies for the cat and dog class as 79% and 69%, respectively.

## Sample Data


## Key Formulas
$x$ is vectorized image</br>
$W$ is the weight vector</br>
$b$ is the bias
- Output for each layer
  - $z = W^Tx + b$


$\theta$ is the weight parameter
$\alpha$ is the learning rate
$\nabla_\theta J(\theta)$ is the gradient
- Backpropagation 
  -   $\theta = \theta -  \alpha \times \nabla_\theta J(\theta)$
