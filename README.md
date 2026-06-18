# Machine Learning Foundations

This repository contains selected machine learning notebooks covering supervised learning, neural networks, and unsupervised density modelling.

## Notebooks

| Notebook | Topic | Main Skills Demonstrated |
|---|---|---|
| `notebooks/01_regression.ipynb` | Regression and regularisation | Feature normalisation, linear regression, MSE, gradient descent, learning-rate tuning, regularised polynomial regression |
| `notebooks/02_classification.ipynb` | Classification and logistic regression | Binary classification, sigmoid function, cross-entropy loss, decision boundaries, one-vs-all classification, softmax accuracy |
| `notebooks/03_neural_networks.ipynb` | Neural networks | Random weight initialisation, feed-forward networks, backpropagation, XOR, MLP classification |
| `notebooks/04_density_estimation.ipynb` | Density estimation and Gaussian mixture models | EM algorithm, Mixture of Gaussians, maximum-likelihood classification, decision-region visualisation, covariance regularisation |

## Technologies Used

- Python
- NumPy
- pandas
- Matplotlib
- Seaborn
- scikit-learn
- SciPy
- PyTorch
- Jupyter Notebook

## Setup

Install the required packages:

```bash
pip install -r requirements.txt
```

Open Jupyter Notebook:

```bash
jupyter notebook
```

Then open the notebooks from the `notebooks/` folder.

## Data Notes

Some notebooks require external data files to be available locally before all cells can be executed. The Gaussian mixture model parameter files used by the density estimation notebook are included in the `data/` folder.

If running the density estimation notebook outside Google Colab, replace the Colab upload cell with a local file path for the source data file.
