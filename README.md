# Neural Network from Scratch – Forward & Backward Pass with NumPy
<br>
Implementing Forward Pass and Backpropagation using Numpy
<br>
<br>
Goal: Is to demonstrate a solid grasp of backpropagation, gradient descent, and the chain rule by implementing a fully functional neural network using only NumPy (without TensorFlow or PyTorch).

<br>
<br>

<h2><b>Network Architecture:</b></h2>
Input layer: 2 neurons
<br><br>
Hidden layer: 3 neurons (ReLU activation)
<br>
Output layer: 1 neuron (linear, no activation)

<br>
<br>

<h2><b> How It Works </b></h2>
<br>
<b> 1. Forward Pass </b> <br>
The forward pass computes the network's output by passing input data through each layer.
<br><br>
<b>Hidden layer:</b>
<br>
Z₁ = X · W₁ + b₁
<br>
H = ReLU(Z₁)

<br>
<br>

<b>For output layer:</b><br>
ŷ = H · W₂ + b₂ (linear output – no activation)

<br>
<br>

<b>Where:</b><br>
X = input (1 × 2) <br>
W₁ = weights from input to hidden (2 × 3) <br>
b₁ = bias for hidden  <br>
H = hidden activation (1 × 3) <br>
W₂ = weights from hidden to output (3 × 1) <br>
b₂ = bias for output  <br>
ŷ = final prediction  <br>
<br>

