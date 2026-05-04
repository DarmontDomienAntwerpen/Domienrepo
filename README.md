# Domienrepo
# Iris Classification with Decision Tree

A simple machine learning notebook that trains a Decision Tree classifier on the classic Iris flower dataset and evaluates its performance on a held-out test set.

## Overview

The notebook (`iris_classifier.ipynb`) walks through a minimal end-to-end ML workflow:

1. **Load data** — Loads the Iris dataset bundled with scikit-learn (150 samples, 4 features, 3 classes: *setosa*, *versicolor*, *virginica*).
2. **Split** — Splits the data into 80% training / 20% testing with a fixed random seed for reproducibility.
3. **Train** — Fits a `DecisionTreeClassifier` on the training data.
4. **Evaluate** — Reports accuracy and a per-class classification report (precision, recall, F1-score) on the test set.

## Requirements

- Python 3.11+
- scikit-learn
- Jupyter (or any notebook-compatible IDE such as PyCharm or VS Code)

## Installation

```bash
pip install scikit-learn jupyter
```

## Usage

Open the notebook and run the cells top-to-bottom:

```bash
jupyter notebook iris_classifier.ipynb
```

## Results

On the 30-sample test set, the model achieves **100% accuracy**, with perfect precision, recall, and F1-score across all three Iris species. (Note: the Iris dataset is small and easily separable, so high accuracy is expected — this is not necessarily indicative of how a Decision Tree would perform on harder datasets.)

## File Structure

```
.
├── iris_classifier.ipynb   # The notebook
└── README.md               # This file
```