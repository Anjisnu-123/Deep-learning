# ANN

- Perceptrons
  - what is a perceptron
  - components of a perceptron
    - inputs
    - weights
    - bias
    - weighted sum
    - activation function
    - example calu
  - Decision boundaries in a perceptron
  - Learning in perceptron
  - Limitations of Single layer pereptron
    - linear separability
    - Step function limitation
  - Applications of perceptron
    - Binary classification
    - Linearly separable problems
  - **MLP**
    - intro
    - Key feature of MLP
      - multilayers
      - Non linear activation function
      - Backprop and optimization
    - Why Mlps are more powerful than SLP?
      - Hidden layer
      - Non linearity
      - universal approximation
    - Architecture of MLP
      - input layer
      - Hidden layers
      - Output layer
      - weight and biases
      - Activation functions
      - feedfwd process
    - Training and back prop in MLP
    - overfitting and regularization
    - learning rate scheduling
    - weight intialization
      - xavier (glorot) initialization
      - He intialization
    - why proper weight intialization matters
    - xavier initialization
      - math basic
      - mechanism
      - use case
    - He initialization
      - mathematical basis
      - mechanism
      - use case
    - Hyperparameter tuning
      - grid seacrh
      - random search
      - bayesian optimization
      - graident based optimization
        
- Transfer learning
  - introeduction
  - Steps in trabsefer learning
    - choose a pre tarined model
    - modify the arch
    - freeze the initial layers
    - Train on new data
    - evaluate and refine
- Challenges in Deep MLP
- Applications of MP

# Deep fed forward neural network
---
- challenges with shallow network
- Advantages of deep architecture
  - increased representation power
  - more....
- Archtecture of deep feed forward neural networks
  - input layer
  - Hidden layer
  - output layer
  - feedfwd operations
- mathematical representation of Deep feed fwd nwural networks
- Addressing gradient problems with proper intialiaztaion
  - xavier initialization
- Batch normalization
  - motivation and intution
  - how batch normalization work
  - benifits of batch normalization
  - key considerations
  - mathematical formula
- Role of batch normalization in deep feedfwd networks
 - challenges in DNN without batch normalization
 - How batch normalization helps
   - stabilizes input distributions
   - improves gradient flow
# resnet
- motivation
- what are residual connections
- resnet architecture
- advantages of residual connections
- mathematical insights
  - residual learning
  - gradient flow
- challenges in DNNs without residual connection
- how residual connection help
  
| Scenario                    | Recommended Technique                                    |
|-----------------------------|----------------------------------------------------------|
| Small Dataset               | L2 Regularization, Dropout, Data Augmentation            |
| Overfitting                 | Dropout, L1/L2 Regularization, Early Stopping            |
| Very Large Dataset          | Dropout, Weight Constraints, Label Smoothing             |
| Robust Against Noise        | Data Augmentation, MixUp, CutMix                         |

# Learning rate and Training stability in DNN
- Role of learning rate in training stability
  - Gradient updates
  - impact on stability
  - Challenges in DNN
- Techniques for managing leanring rate
  - learning rate schedulers
  - Adaptive learning rate methodsGradient clipping
  - Batch normalization
  - residual conn

# Hyper parameter tuning in deep neural networks
- Techniques for hyperparameter tuning
  - grid search
  - random search
  - bayesian optimization
  - Gradient descent optimization
  - hyperband
- Best practices for hyperparameter tuning
- impact of hyperparameter tuning
- Advanced technique for hyperparameter tuning
- population based training
  - description
  - how it works
  - advantages
  - limitations
  - tools : Tensorflow tuner,ray tune
- Evolutionary algorithms
  - Description
  - How it works
  - Advantages
  - Limitations
- Neural architecture Search(NAS)
  - Description
  - How it works
  - Advantages
  - Limitations
  - tools : auto keras,auto ml,nasnet
- Multifidelity optimization
  - Description
  - How it works
  - Advantages
  - Limitations
 
# Interpretability and explainability
- what is interpretability and explainability
- why are this impotant?
- Key techniqes for interpretability and explainability
- challenges in explainability
- balancing interpretability
- application of explainability
