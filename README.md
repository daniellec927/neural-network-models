# Neural Network Models

From-scratch **NumPy** implementations of classic neural-network and associative-memory
models, built to understand how simple learning rules and network dynamics give rise to
memory, discrimination, and competition. No deep-learning frameworks — every model is
implemented directly from the underlying math.

## Notebooks

| Notebook | Topic |
|---|---|
| [`01_random_distributions.ipynb`](01_random_distributions.ipynb) | Random number generation and probability distributions — uniform sampling and approximating a Gaussian via the central-limit approach |
| [`02_pattern_association.ipynb`](02_pattern_association.ipynb) | Linear associator — single and multiple pair association, discrimination, and cosine-based recall quality |
| [`03_network_dynamics.ipynb`](03_network_dynamics.ipynb) | Recurrent-network dynamics — oscillation, convergence, deterioration under noise, and sequential learning |
| [`04_lateral_inhibition.ipynb`](04_lateral_inhibition.ipynb) | Lateral-inhibition and winner-take-all networks |
| [`05_associative_memory_classifier.ipynb`](05_associative_memory_classifier.ipynb) | Linear associator used as a feature-to-label classifier, with feature selection and missing-data handling |
| [`06_feedforward_parity.ipynb`](06_feedforward_parity.ipynb) | Feedforward network trained on a parity task, evaluated over many random trials |

## Tech stack

Python · NumPy · matplotlib

## Getting started

```bash
pip install -r requirements.txt
jupyter notebook
```

Each notebook is self-contained and runs top to bottom with no external data.
