# 2D Gaussian Bayesian Neural Network

---

## Overview

This repository contains the source code and documentation for the paper "2D Gaussian Bayesian Neural Network" submitted to the AAAI conference. The implementation includes the model architecture, training scripts, evaluation metrics, and supplementary materials necessary for replicating the results presented in the paper.

## Repository Structure

```plaintext
.
├── bnn/                      # Bayesian Neural Network related code
├── checkpoint/               # Directory for storing checkpoints
├── checkpoints/              # Additional directory for checkpoints
├── cifar10_models/           # Models specific to CIFAR-10 experiments
├── conf/                     # Configuration files
├── data/                     # Directory for datasets
├── data2/                    # Additional datasets
├── demo_bnns/                # Demonstrations of Bayesian Neural Networks
├── figs/                     # Directory for storing figures
├── models/                   # Directory for model definitions
├── params/                   # Directory for parameter files
├── resnet50/                 # ResNet-50 related files
├── runs/                     # Directory for experiment runs and logs
├── visualize/                # Visualization utilities
├── .gitattributes            # Git attributes file
├── .gitignore                # Git ignore file
├── tasks/                    # Task-specific scripts
├── README.md                 # Project overview and setup instructions
├── Val_acc_bnn_freeze_mu_0.1.txt  # Validation accuracy logs
├── a.png                     # Sample image file
├── a2.png                    # Additional sample image file
├── 1.py                      # Python script
├── bnns_test.py              # Bayesian Neural Network testing script
├── check_weight.py           # Script to check weights
├── cifar10_exp_stochastic_nn.py  # CIFAR-10 experiment with stochastic neural network
├── cifar10_train.py          # CIFAR-10 training script
├── cifar10_utils.py          # Utility functions for CIFAR-10
├── cifar10_visualize.py      # Visualization script for CIFAR-10 results
├── cifar100_visualize.py     # Visualization script for CIFAR-100 results
├── csdn.py                   # CSDN related script
├── dataset.py                # Dataset handling script
├── exp_stochastic_nn.py      # Experiment with stochastic neural network
├── gmm_load.py               # Script for loading Gaussian Mixture Model
├── gmm_train.py              # Training script for Gaussian Mixture Model
├── gmm_train_backup.py       # Backup training script for Gaussian Mixture Model
├── gmm.py                    # Gaussian Mixture Model related script
├── init_weights.py           # Script for initializing weights
├── lr_finder.py              # Learning rate finder script
├── no_exp_stochastic_nn.py   # No experiment stochastic neural network script
└── original_stochastic_nn.py # Original stochastic neural network script
```

## Installation

To get started, clone the repository and install the required dependencies:

```
git clone https://github.com/anonymous/2D-Gaussian-Bayesian-Neural-Network.git
cd 2D-Gaussian-Bayesian-Neural-Network
pip install -r requirements.txt
```

## Usage

### Data Preparation

Place your datasets in the `data/` or `data2/` directory. The expected structure and format should be detailed in a separate documentation or within the scripts themselves.

### Training

To train the model, run the following command:

```

python scripts/train.py --config conf/train_config.yaml
```

### Evaluation

After training, evaluate the model using:

```
python scripts/evaluate.py --model-path checkpoints/trained_model.pth --data-path data/test/
```

### Notebooks

Jupyter notebooks are provided in the `notebooks/` directory for interactive exploration and visualization:

```
jupyter notebook notebooks/
```

## Results

Results, including logs and model checkpoints, will be saved in the `runs/` directory.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
