# Hands-On Machine Learning with Scikit-Learn, Keras, and Tensorflow Concepts Study plan
* P37: pre-train data
  1. Look at the big picture.
  2. Get the data.
  3. Discover and visualize the data to gain insights.
  4. Prepare the data for Machine Learning algorithms.
  5. Select a model and train it.
  6. Fine-tune your model.
  7. Present your solution.
  8. Launch, monitor, and maintain your system.
* P281:Logical Computations with Neurons-- review the concepts
* P322: deep learning exercise-- find all the answers 

  2. Draw an ANN using the original artificial neurons (like the ones in Figure 10-3)
  that computes A ⊕ B (where ⊕ represents the XOR operation). Hint: A ⊕ B = (A
  ∧ ¬ B) ∨ (¬ A ∧ B).
  3. Why is it generally preferable to use a Logistic Regression classifier rather than a
  classical Perceptron (i.e., a single layer of threshold logic units trained using the
  Perceptron training algorithm)? How can you tweak a Perceptron to make it
  equivalent to a Logistic Regression classifier?
  4. Why was the logistic activation function a key ingredient in training the first
  MLPs?
  5. Name three popular activation functions. Can you draw them?
  6. Suppose you have an MLP composed of one input layer with 10 passthrough
  neurons, followed by one hidden layer with 50 artificial neurons, and finally one
  output layer with 3 artificial neurons. All artificial neurons use the ReLU activation
  function.
  • What is the shape of the input matrix X?
  • What about the shape of the hidden layer’s weight vector Wh, and the shape of
  its bias vector bh?
  • What is the shape of the output layer’s weight vector Wo, and its bias vector bo?
  • What is the shape of the network’s output matrix Y?
  • Write the equation that computes the network’s output matrix Y as a function
  of X, Wh, bh, Wo and bo.
  7. How many neurons do you need in the output layer if you want to classify email
  into spam or ham? What activation function should you use in the output layer?
  If instead you want to tackle MNIST, how many neurons do you need in the output
  layer, using what activation function? Answer the same questions for getting
  your network to predict housing prices as in Chapter 2.
  8. What is backpropagation and how does it work? What is the difference between
  backpropagation and reverse-mode autodiff?
  9. Can you list all the hyperparameters you can tweak in an MLP? If the MLP overfits
  the training data, how could you tweak these hyperparameters to try to solve
  the problem?
  10. Train a deep MLP on the MNIST dataset and see if you can get over 98% precision.
  Try adding all the bells and whistles (i.e., save checkpoints, use early stopping,
  plot learning curves using TensorBoard, and so on).
