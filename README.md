# PyTorch
PyTorch is an open source deep learning framework for Python that was developed mainly by Facebook’s AI research group.

PyTorch provides a rich library of deep learning models.
Numpy cannot utilize GPUs to accelerate its numerical computations. For modern deep neural networks, GPUs often provide speedups of 50x or greater, so unfortunately numpy won’t be enough for modern deep learning.
PyTorch also provides tools to calculate automatic differentiation. Hence we do not need to mannually calculate the gradients for updating parameter on our neural network model.

Pytorch Tensor

Tensors are a specialized data structure that are very similar to arrays and matrices. In PyTorch, we use tensors to encode the inputs and outputs of a model, as well as the model’s parameters.

Tensors are similar to NumPy’s ndarrays, except that tensors can run on GPUs or other specialized hardware to accelerate computing. Tensors are also optimized for automatic differentiation (we’ll see more about that later)
