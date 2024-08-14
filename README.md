# Multi-view Graph Convolutional Networks with Attention Mechanism

This repository implements MAGCN, a novel Graph Convolutional Network model that uses multi-view topologies and an attention mechanism to enhance node classification on graph data. The model achieves state-of-the-art results on benchmark datasets like Cora, Citeseer, and Pubmed. Perfect for researchers in graph-based machine learning. [Read the associated paper](https://www.sciencedirect.com/science/article/abs/pii/S0004370222000480).


## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Datasets](#datasets)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

This project presents the implementation of Multi-view Graph Convolutional Networks (MAGCN) with an Attention Mechanism. The proposed method improves the performance of GCNs by incorporating multiple graph topologies and using an attention mechanism to weigh the importance of each view. The experimental results demonstrate state-of-the-art accuracies on benchmark datasets such as Cora, Citeseer, and Pubmed.

## Features

- **Multi-view Learning:** Supports the integration of multiple graph topologies.
- **Attention Mechanism:** Weights different views to improve model performance.
- **State-of-the-Art Performance:** Outperforms existing models on node classification tasks.
- **Robustness:** Demonstrates improved robustness under topology attacks.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/MAGCN.git
   cd MAGCN
   ```

2. **Install the necessary packages:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Install additional dependencies if needed:**

   Ensure that all required Python libraries such as `networkx`, `numpy`, `scipy`, and `torch` are installed. You can install them via pip:

   ```bash
   pip install networkx numpy scipy torch
   ```

## Usage

1. **Load the Jupyter Notebook:**

   Open the `MAGCN.ipynb` notebook using Jupyter to explore the implementation and run the experiments.

   ```bash
   jupyter notebook MAGCN.ipynb
   ```

2. **Run the Experiments:**

   Follow the steps in the notebook to reproduce the results from the paper. Ensure that the datasets (Cora, Citeseer, Pubmed) are available in the appropriate directories or download them using the provided links in the notebook.

3. **Modify and Experiment:**

   You can modify the parameters and experiment with different settings in the notebook to observe how the model's performance changes.

## Datasets

The project uses the following datasets:

- **Cora**
- **Citeseer**
- **Pubmed**

These datasets represent citation networks where nodes are documents and edges represent citation relationships. The node features are bag-of-words vectors representing the content of the documents.

## Results

The results of our method on the benchmark datasets are as follows:

| Dataset  | Accuracy (%) |
| -------- | ------------ |
| Cora     | 81           |
| Citeseer | 72           |
| Pubmed   | 80           |

For detailed experimental results and robustness analysis, please refer to the `Results` section in the notebook or the accompanying paper.

## Contributing

We welcome contributions to enhance this project. Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

We would like to thank the authors of the paper "Multi-view Graph Convolutional Networks with Attention Mechanism" and the contributors to the related libraries used in this project.
