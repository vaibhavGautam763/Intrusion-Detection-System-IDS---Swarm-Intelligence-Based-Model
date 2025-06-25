
# 🛡️ Intrusion Detection System (IDS) - Swarm Intelligence

This project involves the implementation of an Intrusion Detection System (IDS) using swarm intelligence algorithms and machine learning techniques for efficient classification of cyber-attacks.

## 📘 Project Overview

The notebook demonstrates the development and evaluation of a model that classifies network traffic into different types of attacks such as:

- Normal
- DOS (Denial of Service)
- Probe
- R2L (Remote to Local)
- U2R (User to Root)

It uses preprocessing techniques and applies classification models trained with optimized features using swarm intelligence techniques.

## 📂 Project Structure

- **Data Reading**: The dataset (`kddcup.data_10_percent_corrected`) and associated names and attack types files are loaded from a local directory.
- **Preprocessing**: Involves handling categorical features, label encoding, and normalization.
- **EDA (Exploratory Data Analysis)**: Distribution plots and correlation heatmaps for better understanding of feature relationships.
- **Modeling**: Multiple machine learning classifiers are trained and evaluated.
- **Evaluation Metrics**: Accuracy, classification report, and confusion matrix are generated.

## 🚀 Technologies Used

- **Python**
- **Pandas, NumPy** – Data handling
- **Matplotlib, Seaborn** – Visualization
- **Scikit-learn** – ML modeling and preprocessing

- *(Optional extensions)* Swarm Intelligence techniques like:
  - Particle Swarm Optimization (PSO)
  - Artificial Bee Colony (ABC)
  - Ant Colony Optimization (ACO)

> 📌 *Note: If swarm algorithms are not yet added in this notebook, placeholders can be created for future work.*

**🔍 Key Features**
- Data preprocessing (encoding, scaling)
- Label transformation into numeric form
- Model training using machine learning algorithms
- Performance evaluation (accuracy, classification report, confusion matrix)
- Experimentation with attack categories

## 📊 Attack Categories

The attacks are grouped into the following categories:
- `Normal`
- `DOS` (Denial of Service)
- `Probe`
- `R2L` (Remote to Local)
- `U2R` (User to Root)

These categories are encoded numerically for machine learning purposes.

## 🚀 Getting Started

**Prerequisites**
- Install required Python packages using:

## 🧪 Running The  Code

### Install Module In Pthon
```python
import os
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

>📎 *Note: The complete implementation is provided in the attached Jupyter Notebook file.*

## 📈 Results

The performance is evaluated using:
- **Accuracy Score**
- **Confusion Matrix**
- **Precision**
- **Recall**
- **F1-score**

## 🧠 Future Scope

- Integration with swarm intelligence for feature selection or classifier optimization.
- Real-time packet capture and classification.
- GUI-based IDS dashboard.

## 📎 How to Use

1. Install Jupyter Notebook and required Python libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
2. Place your dataset and the `.ipynb` file in the same folder.
3. Run the notebook to see data preprocessing, training, and evaluation in action.

**Author**
# Vaibhav Gautam
