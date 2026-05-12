# Qiskit Finance Tutorial Environment Setup

This guide sets up the `qfin` conda environment for running all 12 qiskit-finance tutorials.

---

## Prerequisites

- Anaconda or Miniconda
- Python 3.12

---

## Setup Steps
```bash
conda create --name qfin python=3.12
conda activate qfin
git clone https://github.com/qiskit-community/qiskit-finance.git
cd qiskit-finance
pip install -r requirements-dev.txt 
pip install qiskit==2.4.1 qiskit-aer==0.17.2 qiskit-algorithms==0.4.0 qiskit-finance==0.4.1 qiskit-optimization==0.7.0  jupyterlab
jupyter lab
```
---

## Package Versions (tested and working)

| Package             | Version |
|---------------------|---------|
| qiskit              | 2.4.1   |
| qiskit-aer          | 0.17.2  |
| qiskit-algorithms   | 0.4.0   |
| qiskit-finance      | 0.4.1   |
| qiskit-optimization | 0.7.0   |
| Python              | 3.12    |

---

