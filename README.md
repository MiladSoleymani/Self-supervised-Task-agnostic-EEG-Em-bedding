# Self-supervised Task-agnostic EEG Embedding

This repository contains code and resources for a self-supervised, task-agnostic EEG embedding model. The primary goal of this project is to develop embeddings for EEG data that can generalize across different tasks without requiring task-specific supervision.

## Table of Contents
- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Repository Structure](#repository-structure)
- [Contributing](#contributing)
- [License](#license)

## Overview
This project implements a self-supervised learning approach to generate task-agnostic embeddings for EEG signals. The embeddings aim to capture the intrinsic properties of the EEG data, allowing for improved generalization across various downstream tasks.

## Installation
To set up the environment, follow these steps:
1. Clone the repository:
    ```bash
    git clone https://github.com/MiladSoleymani/Self-supervised-Task-agnostic-EEG-Embedding.git
    cd Self-supervised-Task-agnostic-EEG-Embedding
    ```
2. Create a virtual environment and install dependencies:
    ```bash
    python -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ```

## Usage
To run the model training, execute the following command:
```bash
python scripts/train.py --config configs/train_config.yaml
```
For more detailed usage, refer to the notebooks provided in the `notebooks` directory.

## Repository Structure
- `configs`: Configuration files for training and evaluation.
- `embedding_feature`: Code related to feature extraction and embedding.
- `notebooks`: Jupyter notebooks for demonstration and analysis.
- `pase_eeg`: Core implementation of the EEG embedding model.
- `scripts`: Scripts for training and evaluation.

## Contributing
We welcome contributions to improve the project. Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
