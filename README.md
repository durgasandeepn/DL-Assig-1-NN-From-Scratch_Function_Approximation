**Neural Network From Scratch — Function Approximation (Deep Learning)**

Overview: Implemented a deep neural network entirely from scratch (no TensorFlow/Keras/PyTorch) to approximate the multiplication function f(x, y) = x·y, using manually coded forward propagation and backpropagation.

Key Components
* Custom NN architecture with 2+ hidden layers, built from raw matrix operations (NumPy only)
* Training data generated as random [xᵢ, yⱼ, xᵢ·yⱼ] triplets with x, y ∈ [0, 1]
* Manual implementation of backpropagation for weight updates
* Experimented with multiple activation functions to identify best performer for this task
* Evaluated using RMSE, with visualization of RMSE over training epochs
* Included validation tests to verify model accuracy on unseen input pairs

Tech stack: Python, NumPy (no deep learning frameworks)

[View the Project in Document format](AssgPrg1.pdf)
