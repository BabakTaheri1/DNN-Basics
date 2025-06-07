This repository contains implementations of deep neural networks (DNNs) with 1 layer, 3 layers, and a generalized L-layer model, inspired by Coursera-style deep learning assignments.

## Files
- `one_layer_dnn.ipynb`: A shallow neural network with one hidden layer.
- `three_layer_dnn.ipynb`: A 3-layer neural network with two hidden layers.
- `l_layer_dnn.ipynb`: A generalized L-layer neural network for flexible depth.
- `cat_image_dnn.ipynb`: A generalized L-layer neural network for cat image classification.

## Requirements
- Python 3.x
- NumPy
- Matplotlib

## How to Use
1. Clone this repository: `git clone <your-repo-url>`
2. Open the Jupyter notebooks in VS Code or Jupyter Notebook.
3. Run the cells to train the models on synthetic binary classification data.
4. Observe the cost reduction plots.

## Notes
- The data is synthetic (2 features, 400 samples) for binary classification.
- Adjust hyperparameters (learning rate, epochs, layer sizes) as needed.
- Models use ReLU for hidden layers and sigmoid for output.