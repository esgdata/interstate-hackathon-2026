# Quantum Machine Learning: Quantum Kernel Classification

## Project Overview

This project explores Quantum Machine Learning (QML) for binary classification using quantum kernel methods and hybrid quantum-classical models.

The objective is to investigate quantum feature maps and compare their classification performance with classical machine learning baselines.

## Problem Statement

The project investigates whether quantum feature maps can improve the representation of nonlinear datasets and examines practical limitations such as measurement shot noise, quantum circuit noise, and quantum kernel concentration.

## Methods and Technologies

- Classical baselines: Linear SVM and RBF Kernel SVM.
- Quantum feature encoding using Qiskit's ZZFeatureMap.
- Quantum kernel estimation using quantum state overlaps.
- Quantum Support Vector Machine (QSVM).
- Variational Quantum Classifier (VQC).
- Analysis of measurement noise and scalability.
- Python, Qiskit, scikit-learn, and Google Colab.

## Reported Results

The project report records the following test accuracies:

| Model | Test accuracy |
|---|---:|
| Linear SVM | 62.5% |
| RBF Kernel SVM | 85.0% |
| Quantum SVM (QSVM) | 98.0% |
| QSVM with noisy execution | 90.0% |
| Variational Quantum Classifier (VQC) | 88.0% |

These results relate to the specific experimental configurations used. They do not, on their own, establish a general quantum advantage. The experimental setup and execution backends should be verified against the notebook.

## Key Challenges

- Sensitivity of quantum kernel estimates to finite measurement shots.
- Impact of noise on quantum circuit execution.
- Quantum kernel concentration as circuit and qubit counts increase.
- Need for reproducible experiments and fair classical comparisons.

## Repository Contents

The repository is intended to contain:

- The Jupyter notebook with the implementation and experiments.
- The project report documenting the methodology and findings.
- Supporting figures and experimental results, where applicable.

## Future Work

- Reproduce experiments across multiple random seeds.
- Strengthen comparisons with classical machine learning models.
- Investigate feature-map design and noise mitigation.
- Explore suitable real-world datasets.

## Project Status

Educational and experimental work focused on implementing and evaluating quantum kernel methods and hybrid quantum-classical classification.

