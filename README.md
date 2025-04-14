# Federated Learning Flavors - Assignment 5

This repository contains solutions and experiments for **Assignment 5: Federated Learning Flavors (FLFlavors)**. The assignment explores different techniques in Federated Learning (FL), focusing on handling data heterogeneity through Clustered Federated Learning (CFL) and Vertical Federated Learning (VFL).

---

## Overview

This project investigates several flavors of Federated Learning, analyzing how various FL strategies perform under different data distributions across clients.

### Key Topics:
- Vertical Federated Learning (VFL)
- Clustered Federated Learning (CFL)
- Global Temperature Variation Minimization (GTVMin)
- K-Means clustering with different client representation strategies

---

## Repository Structure

| File | Description |
|------|-------------|
| `Assignment5_FLFlavors.ipynb` | Main notebook with code, implementations, and detailed explanations. |

---

## Techniques Implemented

### Vertical Federated Learning (VFL)
- Data Points: Hourly weather data from FMI stations across Finland.
- Target Variable: Average temperature across all stations in the next hour.
- Methodology: Use zero-gradient condition to solve GTVMin in matrix form.

### Clustered Federated Learning (CFL)
- Motivation: Handling non-i.i.d (heterogeneous) client datasets.
- Approach: Clustering clients into groups with similar distributions.

### Client Representation Strategies for Clustering
- K-Means with:
  - Geographical Coordinates
  - Gaussian Mixture Model (GMM) Parameters
  - Laplacian Eigenvectors of Graph Representations

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/FLFlavors-Assignment5.git
cd FLFlavors-Assignment5
```

2. Install required Python packages:
```bash
pip install -r requirements.txt
```

---

## Usage

Run the notebook locally:

```bash
jupyter notebook Assignment5_FLFlavors.ipynb
```

Or open directly in Google Colab (if applicable).

---

## Results & Analysis

- Performance comparison of different FL strategies.
- Visualization of clustering results.
- Analysis of heterogeneity handling in FL.
- Theoretical question answers included.

---

## References

- *Federated Learning* by Jakub Konečný, H. Brendan McMahan, Daniel Ramage
- FLBook — Sections 3.4 and 6.3
- Finnish Meteorological Institute (FMI) weather data

---




