# Neural-Networks-CNNs-on-Shifted-MNIST

This project implements and evaluates feedforward neural networks (MLPs) and convolutional neural networks (CNNs) in PyTorch on spatially shifted MNIST datasets. The goal is to study how different architectures handle positional variations in images.

Key Features

	•	Shifted MNIST preprocessing: Created top-left and bottom-right shifted versions of MNIST to test model robustness.
	•	MLP architectures: Two multi-layer perceptrons with one and two hidden layers respectively, using ReLU activations and log-softmax output.
	•	CNN architecture: Convolutional network with two convolution + max-pooling blocks, followed by a dense classifier.
	•	Training pipeline: Implemented training loops with negative log-likelihood loss and Adam optimizer.
	•	Performance evaluation: Measured accuracy on both original and shifted datasets, demonstrating CNN superiority on spatially shifted inputs.

Results

	•	CNN achieved ~99% accuracy on shifted test data.
	•	MLPs achieved only ~51% accuracy, showing the advantage of convolutional architectures for positional invariance.

Tools & Technologies

	•	Python, PyTorch, Torchvision, Matplotlib
	•	DataLoader and custom preprocessing for shifted MNIST
	•	Visualization of example digits and model outputs


<img width="71" height="349" alt="image" src="https://github.com/user-attachments/assets/8ee89307-0836-4e4c-afd8-e9f3e009faf1" />
