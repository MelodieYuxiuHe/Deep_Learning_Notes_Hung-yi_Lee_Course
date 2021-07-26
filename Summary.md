# Summary

Learning based on 2 courses from Hung-yi Lee.

https://www.youtube.com/c/HungyiLeeNTU/playlists

https://www.youtube.com/watch?v=Ye018rCVvOo&list=PLJV_el3uVTsMhtt7_Y6sgTHGHp1Vb2P2J

Slides: https://speech.ee.ntu.edu.tw/~tlkagk/courses_ML16.html

## Topics covered:

- Definition of ML: A set of functions >>> Evaluate >>> Select
- Regression: 
  - e.g. a set of functions (to measure relationship between pre-evolve CP and post-evolve CO) >>> define the RMS loss function >>> select the best function using linear algebra/gradient descent >>> Redesign the function using regularization >>> Measure the performance of function again

- Error Analysis and Adagrad: 

  Bias and variance of estimator: the trade-off

  For large bias: add more features/a more comples model

  For large variance: more data/regularization

- Model Selection:

  - Select a model at the balance of two errors
  - Have a CV dataset
  - n-fold CV

- DL: 

  - A set of different functions connected together. Each function has its own bias and weight.
  - DL we design the structure of the network (similar to ML function selection)
  - Input layer >>> hidden layer >>> output layer

- Problems and Solutions while training a NN:

  - Local minima and Saddle Point:
    - Saddle Point: >>> Hessian matrix and know the direction to 'escape'
    - Change the dimension of features
  - Batch and Momentum:
    - Batch and Epoch
    - Select between small batch and large batch: 
      - smaller batch size 'noisy update' is better for training
      - smaller batch size is better on testing (sharp and flat minima)
      - Smaller batch faster , slower for one epoch, noisy for gradient, better at optimization and generalization.
    - Momentum:
      - Gradient Descent + Momentum: consider the movement of last step
  - Adaptive Learning Rate:
    - Adagrad

- CNN

  - CNN for image: 
    - some patterns are smaller than the whole image. A neuron doesn't have to see the whole image to discover pattern.
    - Same pattern appears multiple times
    - Subsampling won't change the object
  - 3 properties for CNN:
    - Convolution Layer (some patterns are smaller)
    - Convolution Layer (some patterns appear multiple time)
    - Max Pooling: Subsampling

## Future Study Plan:

- Homework
- The complete video

