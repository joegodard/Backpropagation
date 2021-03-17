# Backpropagation
This is an implementation of the backpropagation algorithm written in python.     
It can run a variety of tests to determine the accuracy of the algorithm based on some given parameters.
At the bottom of the `backpropagate.py` file, the user can tweak the inputs of the `evaluate_algorithm` method to see how different inputs affect the performance.     

## Parameters in the Tests
- **Folds:** A fold is a subsection of the data in the csv, each fold is evaluated separately and given an accuracy percentage, then the mean accuracy is taken from the average of all the fold scores.
- **Learning Rate:** The learning rate determines how quickly the weights of nodes in the backpropagation algorithm are updated. Low learning rates may be very slow as the weights are only updated in very small increments, while high learning rates (rates approaching 1) can cause changes that are too large, which can cause the result to jump around erratically.
- **Epochs:** This is the number of times the algorithm will backpropagate the error through the nodes and update their weights. A higher number of epochs will lead to a higher precision.
- **Hidden Nodes:** The number of nodes in the hidden layer of the neural network

# Example Test
![Example Test](https://github.com/joegodard/Backpropagation/blob/main/Images/ExampleTest.png?raw=true)
