# Graph Neural Networks

This repository contains implementations, experiments, and research notes related to Graph Neural Networks (GNNs). GNNs are a class of neural networks designed to perform inference on data described by graphs, enabling powerful modeling of relationships between entities.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [References](#references)

## Overview

Graph Neural Networks are widely used in various domains such as social network analysis, knowledge graphs, recommendation systems, and bioinformatics. This project aims to provide both foundational and advanced GNN models, utilities for graph data processing, and scripts for running common experiments.

## Features

- Implementation of popular GNN architectures (e.g., GCN, GAT, GraphSAGE)
- Utilities for graph data loading and preprocessing
- Training and evaluation scripts
- Example datasets and experiment configs
- Modular and extensible codebase

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Maede-mim/Graph-Neural-Networks.git
    cd Graph-Neural-Networks
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

    > **Note:** The code is compatible with Python 3.8+.

## Usage

You can train and evaluate models using the provided scripts. Example:

```bash
python train.py --model GCN --dataset Cora --epochs 200
```

For more options, run:

```bash
python train.py --help
```

## Project Structure

```
Graph-Neural-Networks/
│
├── data/               # Example graph datasets
├── models/             # GNN model implementations
├── utils/              # Utility functions and classes
├── experiments/        # Experiment configs and results
├── train.py            # Training script entry point
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
```

## Examples

### Training a GCN on the Cora dataset

```bash
python train.py --model GCN --dataset Cora --epochs 200
```

### Training a Graph Attention Network (GAT)

```bash
python train.py --model GAT --dataset PubMed --epochs 200
```

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements, bug fixes, or new features.

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## References

- Kipf, T.N. & Welling, M. (2016). Semi-Supervised Classification with Graph Convolutional Networks. [arXiv:1609.02907](https://arxiv.org/abs/1609.02907)
- Velickovic, P., et al. (2017). Graph Attention Networks. [arXiv:1710.10903](https://arxiv.org/abs/1710.10903)
- Hamilton, W., Ying, R., & Leskovec, J. (2017). Inductive Representation Learning on Large Graphs. [arXiv:1706.02216](https://arxiv.org/abs/1706.02216)

---

Feel free to reach out if you have any questions or suggestions!
