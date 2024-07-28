# 2D Gaussian Bayesian Neural Network

---

## Overview

```
This repository contains the source code and documentation for the paper "2D Gaussian Bayesian Neural Network" submitted to the AAAI conference. 
```

## Repository Structure

```
.
├── .git/                                # Git repository files
├── bnn/                                 # Bayesian Neural Network related code
├── checkpoints/                         # Directory for storing checkpoints
├── conf/                                # Configuration files
├── data/                                # Directory for datasets
├── models/                              # Directory for model definitions
├── params/                              # Directory for parameter files
├── README.md                            # Project overview and setup instructions
├── gmm_train.py                         # Training script for Gaussian Mixture Model
├── stochastic_nn.py                     # Script for stochastic neural network
├── train.py                             # Training script
├── utils.py                             # Utility functions
└── visualize_stochastic_weights_scatter.py  # Visualization script for stochastic weights scatter
```

## Installation

```
To get started, clone the repository and install the required dependencies:

git clone https://github.com/anonymous/2D-Gaussian-Bayesian-Neural-Network.git
cd 2D-Gaussian-Bayesian-Neural-Network
pip install -r requirements.txt
```

## Usage

### Data Preparation

```
Place your datasets in the `data/` directory. The expected structure and format should be detailed in a separate documentation or within the scripts themselves.
```

### Training

```
To train the model, run the following command:

python train.py --config conf/train_config.yaml
```

### Evaluation

```
After training, evaluate the model using:

python evaluate.py --model-path checkpoints/trained_model.pth --data-path data/test/
```

### Visualization

```
To visualize the stochastic weights scatter, run the following script:

python visualize_stochastic_weights_scatter.py
```

## Results

```
Results, including logs and model checkpoints, will be saved in the `checkpoints/` directory.
```

## Visualization Example

```
![Visualization](a.png)

*Figure 1: Weights distribution and clusters by 2D Gaussian*
```

## License

```
This project is licensed under the MIT License. See the `LICENSE` file for details.
```
