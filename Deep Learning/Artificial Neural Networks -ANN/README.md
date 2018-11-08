# Training an ANN with Stochastic Gradient Descent #
* STEP 1:
  * Randomly initialise the weights to small numbers close to 0 (but not 0).
* STEP 2:
  * Input the firts observation of your Dataset in the input layer, each feature in one input node.
* STEP 3:
  * Forward-Propegation: from the left to right. the neurons are activated in a way that the impact of each neuron's activation is limited
    by the weights. Propagate the activationsuntill getting the predicted result.
* STEP 4:
  * Compare the predicted result to the actual result. Measure the generated error.
* STEP 5:
  * Back-Propegation: frome right to left, the error is back propegated. Update the weights according ti how mucvh they are responsible for     the error. The learning rate decides by how much we update the weights.
* STEP 6:
  * Repeat steps 1 to 5 and update the weights only after each observations (Reinforcement Learning).
    Or:
    Repeat steps 1 to 5 and update the weights only after a batch of observations (Batch Learning).
* STEP 7:
  * When the whole training set passed through the ANN, that makes an epoch. Redo more epoches.
