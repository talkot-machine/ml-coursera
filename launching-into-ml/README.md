- models are set of params + hyper-params
- find best params optimizing loss fn (using GD)

What is the key difference between supervised and unsupervised models?
- Supervised models learn to predict based on known labels whereas 
unsupervised models are more concerned with discovering patterns in the dataset

Select the model you would try first if you had labeled, non-continuous value data?
- Classification

```
LR -> Perceptron -> NN -> Decision tree -> Kernel methods/ SVMs -> Random Forrests
```

What is a `hyperparameter` that helps determine gradient descent’s step size along the hypersurface to hopefully speed up convergence?
- Hyperparameters are settings that can be tuned to control the behavior of a machine learning algorithm.
- https://medium.com/@jrodthoughts/knowledge-tuning-hyperparameters-in-machine-learning-algorithms-part-i-67a31b1f7c88
- answer: learning rate, this process iterates until convergance(ML History)

What component of a biological neuron is analogous to the input portion of a perceptron?
- Dentrites

What is important when creating deep neural networks?
- Lots of data
- Experimentation
- Having good generalization
- http://playground.tensorflow.org/#activation=relu&regularization=L2&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=&seed=0.84062&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false&showTestData_hide=true&learningRate_hide=true&regularizationRate_hide=true&percTrainData_hide=true&numHiddenLayers_hide=false&discretize_hide=true&activation_hide=false&problem_hide=true&noise_hide=true&regularization_hide=true&dataset_hide=true&batchSize_hide=false&playButton_hide=false
- spiral dataset http://playground.tensorflow.org/#activation=relu&batchSize=10&dataset=spiral&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=&seed=0.53586&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false&showTestData_hide=true&activation_hide=false&problem_hide=true&noise_hide=true&discretize_hide=true&regularization_hide=true&dataset_hide=true&batchSize_hide=false&learningRate_hide=true&regularizationRate_hide=true&percTrainData_hide=true&numHiddenLayers_hide=false

If I wanted my outputs to be in the form of probabilities which activation function should I use in the final layer?
- Sigmoid has a range of [0-1] as in probability

True or False - a decision tree is always a good model to pick because it is to visually appealing to business users
- F

In a decision classification tree, what does each decision or node consist of?
- Linear classifier of one feature

We’ve seen how SVMs use kernels to map the inputs to a higher dimensional feature space. 
What thing in neural networks(NN) also can map to a higher dimensional vector space?
- More neurons per layer

Which of the following is most likely true of random forests when comparing against individual decision trees?
- Better generalization through bagging/subspacing
- Has wisdom of the crowd through voting/aggregating
- Similar bias but lower variance

You own a winter ski resort and want to predict the traffic levels of ski runs based on four types of customers (beginner, intermediate, advanced, expert) that have bought tickets and the amount of previous snowfall.
- It would be regression if the traffic level for each category(beginner, intermediate, advanced, expert) is in numbers, given tickets and snowfall as features.

It would be Classification is traffic level for each category (beginner, intermediate, advanced, expert) is in group like high or low or average, given tickets and snowfall as features.