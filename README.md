# Deep Learning Research Projects

Research-oriented deep learning projects exploring robustness attacks on neural networks and transformer-based architectures.

## Overview

This repository contains implementations and experiments developed as part of the Technion course:

**CS236781 – Deep Learning on Computational Accelerators**

The project focuses on:

* Reproducing and analyzing recent research papers.
* Investigating robustness attacks on neural networks.
* Exploring attack strategies on CNNs and Transformer-based models.
* Performing experimental evaluation and ablation analysis.

---

## Main Topics

### DNL / 1-Pass DNL Attacks

Implementation and analysis of:

* Data-Free Neural Network Disruption (DNL)
* 1-Pass DNL attacks
* Pass-free attack variants
* Attention-specific attacks on Q / K / V layers

Experiments were conducted on both convolutional and transformer-based architectures.

---

## Experiments

The notebook includes multiple experiments and evaluations, including:

* Baseline DNL attacks
* 1-pass DNL variants
* Transformer attention ablations
* Q-only / K-only / V-only attacks
* QK / QV / KV combined attacks
* Accuracy degradation analysis

---

## Technologies

* Python
* PyTorch
* TorchVision
* Transformers / BERT
* CUDA
* Jupyter Notebook

---

## Repository Structure

```text
final_project.ipynb   Main notebook containing all implementations and experiments
```

---

## Running the Project

Install dependencies:

```bash
pip install torch torchvision transformers
```

Run the notebook:

```bash
jupyter notebook final_project.ipynb
```

---

## Authors

* Daniel Elgarici
* Tal Banjo
