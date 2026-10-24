# Quantum Machine Learning: Quantum Kernel Classification

## Project Overview

This project explores Quantum Machine Learning (QML) for binary classification using quantum kernel methods and hybrid quantum-classical models.

The objective is to investigate quantum feature maps, compare their classification performance with classical machine learning baselines, and examine the practical limitations of quantum kernel methods.

This project was developed for the **Interstate Quantum Hackathon 2026 — Rising-Star track**, with a focus on Quantum Kernels.

## Problem Statement

Classical machine learning models can struggle with certain nonlinear classification problems. Quantum kernel methods offer an alternative approach by encoding classical data into quantum states and estimating similarities in a quantum feature space.

This project investigates whether quantum feature maps can improve classification performance on selected datasets while examining measurement shot noise, quantum circuit noise, kernel concentration, and scalability.

## Methods and Technologies

- **Classical baselines:** Linear SVM and RBF Kernel SVM.
- **Quantum feature encoding:** Qiskit's ZZFeatureMap.
- **Quantum kernel estimation:** Quantum state overlap measurements.
- **Quantum classification:** Quantum Support Vector Machine (QSVM).
- **Hybrid quantum-classical learning:** Variational Quantum Classifier (VQC).
- **Noise and scalability analysis:** Measurement uncertainty and quantum kernel concentration.
- **Technologies:** Python, Qiskit 2.x, Qiskit Machine Learning, scikit-learn, NumPy, SciPy, and Google Colab.

## Reported Results

The project report records the following test accuracies:

| Model | Test accuracy |
|---|---:|
| Linear SVM | 62.5% |
| RBF Kernel SVM | 85.0% |
| Quantum SVM (QSVM) | 98.0% |
| QSVM with noisy execution | 90.0% |
| Variational Quantum Classifier (VQC) | 88.0% |

These figures correspond to the specific experimental configurations described in the project report. They should be interpreted as preliminary experimental results rather than evidence of general quantum advantage.

The dataset, evaluation procedure, and execution backend should be verified against the notebook. In particular, noisy simulation results must be distinguished from experiments performed on real quantum hardware.

## Key Challenges

- Sensitivity of quantum kernel estimates to finite measurement shots.
- Impact of noise on quantum circuit execution.
- Quantum kernel concentration as circuit complexity and qubit count increase.
- Computational cost and scalability of quantum kernel evaluation.
- Reproducibility and fair comparisons with classical machine learning models.

## Repository Contents

The repository is intended to contain:

- The Jupyter notebook with the implementation and experiments.
- The project report documenting the methodology and findings.
- Supporting figures and experimental results, where applicable.

## Future Work

- Reproduce experiments across multiple random seeds.
- Strengthen comparisons with appropriately tuned classical machine learning models.
- Investigate quantum feature-map design and noise mitigation.
- Evaluate performance on additional classification datasets.
- Document execution backends, circuit configurations, and experimental parameters for reproducibility.

## Project Status

Educational and experimental work focused on implementing and evaluating quantum kernel methods and hybrid quantum-classical classification.

**Author:** Sidi Mohamed EL ALAOUI  
**Event:** Interstate Quantum Hackathon 2026  
**Track:** Quantum Machine Learning (QML) — Quantum Kernels  
**Category:** Rising-Star
