# Ada-Graph: Closing the Gap Between Structural Expressivity and Practical Robustness in GNN-based Network Intrusion Detection

This repository contains the official implementation of the paper **"Ada-Graph"** submitted to *IEEE Transactions on Network Science and Engineering (TNSE)*.

## 📌 Overview

Network traffic naturally exhibits a directed multigraph structure. **Ada-Graph** extends Egressy's structural backbone with three novel components designed for practical NIDS:

1. **Smart Embedding**: Integrates rolling statistics and learnable port embeddings.
2. **Robustness Module**: Combines multi-scale aggregation and structural dropout to handle noise and imbalance.
3. **DX-Loss**: A unified objective integrating logit adjustment, difficulty-aware weighting, temporal annealing, and **ante-hoc interpretability** (Fidelity, Sparsity, PEAR).

## 🛠️ Requirements & Installation

We recommend using a virtual environment (Python 3.10+).

```bash
pip install -r requirements.txt
```

## 🚀 Usage

Open the Jupyter Notebook to run the data preprocessing, model training, and ablation studies:

```bash
jupyter notebook Ada_Graph_Implementation.ipynb
```

## 📊 Datasets

The model is evaluated on standard benchmark datasets (UNSW-NB15-v3, CIC-IDS-2018-v2, ToN-IoT-v2, BOT-IoT).

*Note: Datasets are not included due to size limits. Please download them from Kaggle.*

## 📜 Citation

If you find this code useful, please cite our paper:

*(Citation will be updated upon publication)*

## ⚖️ License

This project is licensed under the terms of the LICENSE file included in this repository.
