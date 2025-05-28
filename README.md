# Scaler_learners_Clustering

## Scaler Learners Clustering

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/raghav1saboo/Scaler_learners_Clustering/blob/main/Scaler_Learners_Clustering.ipynb)

## Overview

This repository contains a Jupyter Notebook that focuses on clustering learners from Scaler based on their job profiles, companies, and other relevant features. The goal is to identify groups of learners with similar characteristics, which can be valuable for profiling top companies and job positions within the Scaler ecosystem.

The analysis explores both manual and unsupervised clustering techniques.

## Problem Statement

The task is to cluster Scaler learners based on their job profile, current employer, and other attributes. These clusters should ideally group learners with similar professional backgrounds and career trajectories. This profiling can help Scaler understand the landscape of companies and job roles their learners are associated with.

## Dataset

The dataset used for this project is `scaler_kmeans.csv`.

## Data Dictionary

| Feature            | Description                                                                                                |
| ------------------ | ---------------------------------------------------------------------------------------------------------- |
| `Unnamed 0`        | Index of the dataset.                                                                                    |
| `Email_hash`       | Anonymised Personal Identifiable Information (PII).                                                       |
| `Company_hash`     | Anonymized identifier for the learner's current employer.                                                |
| `orgyear`          | Employment start date.                                                                                   |
| `CTC`              | Current CTC (Cost To Company).                                                                           |
| `Job_position`     | Job profile in the company.                                                                              |
| `CTC_updated_year` | Year in which CTC got updated (likely due to yearly increments or promotions).                             |

## Concepts Used

The Jupyter Notebook implements the following clustering concepts:

* **Manual Clustering:** Exploring initial groupings based on domain knowledge or specific features.
* **Unsupervised Clustering - K-Means:** Applying the K-Means algorithm to partition learners into clusters.
* **Unsupervised Clustering - Hierarchical Clustering:** Utilizing hierarchical clustering methods to identify relationships between learners.

## Getting Started

1.  Clone this repository to your local machine:
    ```bash
    git clone [https://github.com/raghav1saboo/Scaler_learners_Clustering.git](https://github.com/raghav1saboo/Scaler_learners_Clustering.git)
    ```
2.  Navigate to the repository directory:
    ```bash
    cd Scaler_learners_Clustering
    ```
3.  Open and run the Jupyter Notebook `Scaler_Learners_Clustering.ipynb`.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

## License

[Optional: Add a license if you have one, e.g., MIT License]
