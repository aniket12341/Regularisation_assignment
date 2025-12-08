# Regularisation in Neural Networks: L2, Dropout, and Early Stopping

This repository contains the code, figures, and tutorial for a machine learning coursework project exploring the effect of regularisation techniques on multilayer perceptrons (MLPs). The tutorial compares L2 regularisation, dropout, and early stopping using a subset of the Fashion-MNIST dataset.

## Contents

- `notebook.ipynb` – The full Jupyter notebook used to run the experiments and generate all plots.
- `tutorial.pdf` – The final written tutorial (under 2000 words).
- `figures/` – All figures produced by the notebook and included in the PDF.
- `requirements.txt` – Python package requirements.
- `LICENSE` – Open-source license for this project.
- `README.md` – Repository documentation.

## How to Run the Notebook

1. Install Python 3.9+  
2. Install dependencies:
3. Open Jupyter:
4. Run `notebook.ipynb` from top to bottom.  
It will:
- Download Fashion-MNIST  
- Train five MLP variants  
- Produce all plots automatically  
- Save figures into the `figures/` folder  

## Experiment Summary

The notebook trains and compares five models:
1. Baseline (no regularisation)
2. L2 regularisation (weight decay = 1e-4)
3. Dropout (p = 0.5)
4. Early stopping (patience = 5)
5. Combined L2 + Dropout

Metrics captured:
- Training loss and accuracy  
- Validation loss and accuracy  
- Final test accuracy  
- Misclassified examples  

## License

This project is released under the MIT License (see LICENSE file).

## Author
Aniket Mane - 23096043

## Course Submission
This repository supports the coursework submission for the Machine Learning module.  
The PDF tutorial and notebook both include a link to this repository, as required.
