# PiGLeT: Probabilistic Message Passing for Semi-supervised Link Sign Prediction 🚀

This repository provides the implementation of **PiGLeT**, a probabilistic message-passing model designed for semi-supervised link sign prediction tasks.

## Project Overview 📌

**PiGLeT** (Probabilistic Message Passing for Semi-supervised Link Sign Prediction) aims to accurately predict link signs (positive or negative) in graphs with partially observed edge labels. It leverages probabilistic message passing to handle uncertainties effectively, enabling robust prediction under label scarcity.

## Requirements 📋

Ensure you have Python installed (recommended Python 3.8+). The required packages are:

```
matplotlib==3.7.5
numpy==1.24.3
scikit_learn==1.3.2
scipy==1.15.3
seaborn==0.13.2
torch==1.13.1
torch_geometric==2.6.1
torch_geometric_signed_directed==0.25.0
torcheval==0.0.7
```

You can install all required dependencies using:

```bash
pip install -r requirements.txt
```

## Installation ⚙️

Clone this repository to your local machine:

```bash
git clone https://github.com/piglet-anonymous/PiGLeT.git
cd PiGLeT
```

## Usage 💻

To train and evaluate the PiGLeT model, use:

```bash
python main.py --epochs 100 --dataset slashdot
```

Modify the arguments in the command line to change datasets, epochs, and other experiment settings.

## Code Structure 📂

* `main.py`: Entry point for running experiments and evaluations.
* `src/train.py`: Contains the training loop logic and performance evaluations.
* `src/utils.py`: Common utility functions.
* `src/model/Piglet.py`: Defines the PiGLeT model architecture.
* `src/model/PigletConv.py`: Implements the probabilistic message-passing convolutional layers.



## Contact 📧

For questions or suggestions, please open an issue on GitHub or email: [piglets2pooh@gmail.com](mailto:your.email@example.com).
