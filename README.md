\# Symmetric Music System — Machine Learning Capstone



\## Overview

This project is a data science and machine learning capstone investigating whether a \*\*mathematically symmetric musical tuning system\*\* can outperform the traditional 12-tone system in precision, harmonic alignment, and predictability.



The analysis uses synthetic chord data, harmonic feature engineering, and multiple machine learning models to test whether the two systems are mathematically distinct.



---



\## Problem Statement

Traditional 12-tone tuning relies on irrational frequency ratios, leading to tuning error and asymmetry.  

This project evaluates a proposed symmetric system based on whole-number ratios and tests whether machine learning can distinguish between the systems based on harmonic properties.



---



\## Dataset

\- 2,000 synthetic chord samples

\- 15 engineered harmonic features

\- Balanced dataset (1,000 traditional / 1,000 symmetric)



Synthetic data is appropriate because musical frequency relationships are governed by mathematical and physical laws, enabling precise and reproducible evaluation.



---



\## Methods

\- Exploratory Data Analysis (EDA)

\- Feature Engineering

\- Train/Test Split (80/20, stratified, fixed random seed)

\- Machine Learning Models:

&nbsp; - Random Forest

&nbsp; - Support Vector Machine (SVM)

&nbsp; - Neural Network

&nbsp; - XGBoost

&nbsp; - Ensemble Model



---



\## Key Results

\- \*\*100% tuning precision\*\* in the symmetric system (vs 81.4% traditional)

\- \*\*100% classification accuracy\*\* across multiple ML models

\- Statistically significant overtone alignment (p < 0.001)

\- Comparable musical consonance between systems



These results indicate the systems are mathematically distinct and perfectly separable using machine learning.



---



\## Repository Structure

├── capstone_project.ipynb # Full analysis and ML pipeline

├── Slides.pdf # Presentation and business context

├── extended\_octave\_data.csv # Dataset used by the notebook

├── setup\_paths.sh # Environment setup (see below)

├── requirements.txt # Python dependencies

└── README.md

├──.gitignore





---



\## How to Run (Notebook Unchanged)

```bash
git clone https://github.com/OneFiftySix/symmetric-music-system-ml.git
cd symmetric-music-system-ml
pip install -r requirements.txt
bash setup_paths.sh
jupyter notebook

### Notes
- The notebook uses an absolute path for the dataset and is not modified.
- `setup_paths.sh` prepares the dataset so the notebook can run as-is.
- On Windows: use WSL (recommended) or manually copy the dataset to the exact path used in the notebook.





Tools \& Technologies

Python

NumPy, Pandas

Matplotlib, Seaborn

Scikit-learn

XGBoost

TensorFlow



Author

Masin Namwar

Data Science \& AI



Notes:

The notebook is intentionally left unchanged to preserve audit integrity.

All reproducibility steps are handled through external setup files.






