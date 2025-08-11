# HASolGNN
Hierarchical-Attention Graph Learning for Solubility Prediction.

This repository contains the code for the reproducibility of the experiments presented in the paper "Hierarchical-Attention Graph Learning for Solubility Prediction". 

This paper proposes HASolGNN, a hierarchical-attention graph neural networks for solubility prediction. (1) HASolGNN adopts a three-level hierarchical attention framework to characterize atom-bond level, molecular level, and interaction-graph level features. This allows a more comprehensive modeling of both intra-molecular and inter-molecular interactions for solute-solvent dissolution as a complex dynamic system. (2) To mitigate the impact of small annotated data, We also investigate the role of Large Language Models (LLMs), and introduce HASolGNN-LLMs, an LLM-enhanced counterpart that leverages LLMs to infer annotated features and embeddings to improve the representation learning. Our experiments verified that (1) HASolGNN outperforms the state-of-the-art methods in solubility prediction; and (2) HASolGNN-LLMs effectively exploit LLMs to enhance sparse annotated data, and further improves the accuracy.

## Organization of the code

All the code for the models described in the paper can be found in *codes. 
We provide the datasets used in our experiments for users to validate our proposed methods located in: *Datasets.

## Prerequisites
Our code is based on Python3 (>= 3.11). The major libraries are listed as follows:
* NumPy (>= 1.26.3)
* Pandas (>= 2.0.1)
* Torch (>= 2.3.1)
* PyG (PyTorch Geometric) (>= 2.0.4)



