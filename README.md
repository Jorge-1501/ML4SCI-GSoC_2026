# ML4SCI-GSoC_2026

This repository contains my solutions for the computational physics exercises and foundational work for Machine Learning in High Energy Physics, supporting my GSoC proposal for ML4SCI.

## 🚀 Completed Exercises

* **Exercise I:** Implementation of fundamental quantum operations and state preparations using standard quantum computing frameworks.
* **Exercise II:** Implementation and comparative analysis of Graph Neural Networks using Graph Attention Networks (GAT) and Message Passing Neural Networks (MPNN) to classify jets as quarks or gluons using [ParticleNet's data](https://zenodo.org/records/3164691#.YigdGt9MHrB).
* **Exercise III:** Detailed explanation of Shor's quantum factoring algorithm, demonstrated through the practical recreation and breaking of the RSA cryptosystem.
* **Exercise IX:** Development and training of a classical Kolmogorov-Arnold Network (KAN) utilizing B-splines on the MNIST dataset, including a detailed architectural sketch for a potential Quantum KAN extension.

## 🛠️ Tech Stack

* **Language:** Python 3.13+
* **Environment Management:** [uv](https://astral.sh/uv) (Ensures reproducible and fast dependency resolution).
* **Core Libraries:** `tensorflow`, `tensorflow-probability`, `tf-keras`, `numpy`, `matplotlib`, `cirq`, `pennylane`.

## 📦 Quick Start

This project uses `uv` to manage dependencies without polluting your global environment.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Jorge-1501/ML4SCI-GSoC_2026.git
   cd ML4SCI-GSoC_2026
    ```
2. **Sync the environment:**
   ```bash
   uv sync
   ```
3. **Activate the environment:**
   ```bash
   .venv/bin/activate
   ```
4. **Run the notebooks:**
   - Open `Task_I/Task_I.ipynb` for the first exercise.
   - Open `Task_II/Task_II.ipynb` for the second exercise.
   - Open `Task_III/Task_III.ipynb` for the third exercise.
   - Open `Task_IX/Task_IX.ipynb` for the ninth exercise.
    select the local .venv kernel in Jupyter.

Developed by Jorge Toral, a Physics student at BUAP.