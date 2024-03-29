
# getting started with fundamentals of AI

-----

## Mathematics of Neural Networks (Teaching MA2608)

Deep learning for 2nd-year undergraduate students in mathematics

1. Use numpy to code a feed-forward fully connected neural network (MLP).

2. Implement and justify backpropagation with calculus and linear algebra.

3. Implement mini-batch stochastic gradient descent (SGD).

4. Implement ReLU and Sigmoid activations.

5. Use squared loss (TSE) and cross-entropy loss (XE).

6. Introduce confusion matrix, precision, and recall.

7. Apply the techniques to the MNIST dataset (in CSV format available on Kaggle) [MNIST Dataset](https://www.kaggle.com/datasets/oddrationale/mnist-in-csv).

The code was written in stages.

In the first notebooks (DL01-07), the focus is on training neural nets from scratch. It involves neural nets of different sizes, activations, and performance indices. They are first trained on a small fraction of dataset (train/test =1000/100) then applied to the original MINST (60k/10k). 

In the later notebooks (DL08-09), I take the object-oriented programming approach and coded the linear layers, the activation layers, loss layer as classes, and provide them with the forward method and backward method.

Although the MLP achieves about 97% accuracy for the MNIST data, this architecture struggles to handle (just slightly) more complicated datasets such as CIFAR10. Indeed, in notebook DL10, I demonstrate that running MLP leads to only 30% accuracy !

Mathematical derivation of the backprop algorithm and a few tricks for training neural networks is given at the end in a PDF.  


-----
