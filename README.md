# SVM Dual Formulation & Kernel Comparison

## Overview

This repository provides an implementation of Support Vector Machines (SVM) using both dual formulation and kernel tricks. It includes a Python script that demonstrates manual SVM dual formulation, and a Jupyter Notebook for exploring and visualizing the results.

## Contents

- `SVM-Dual-Formulation-Kernel-Comparison` : Jupyter Notebook with examples and visualizations of SVM dual formulation, linear SVM, and kernel SVM (RBF kernel).

## Installation

To run the scripts and notebook, clone this repository and install the required packages:

```bash
git clone https://github.com/RudraxDave/SVM-Dual-Formulation-Kernel-Comparison.git
cd SVM-Dual-Formulation-Kernel-Comparison
pip install numpy matplotlib scikit-learn
```

## Usage

### Running SVM Dual Formulation

The svm_dual.py script demonstrates the SVM dual formulation and plots the decision boundaries for different data points.

```bash
from svm_dual import iteration

# Testing the SVM dual formulation with different third data points
iteration([0, 0])  # First dataset, simple case
iteration([1, 1])  # Second dataset, changes the margin slightly
iteration([0, 1.5])  # Third dataset, significant change in decision boundary
```

### Using the Jupyter Notebook

Open the Jupyter Notebook to explore and visualize the SVM models:
```bash
jupyter notebook SVM_Comparison_Notebook.ipynb
```

The notebook includes:

Visualizations of the decision boundaries.
Comparisons between linear and kernel SVM models.
Interactive exploration of different datasets and parameters.

## Examples

Refer to the Jupyter Notebook for detailed examples and visualizations.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request with any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- **[Scikit-Learn](https://scikit-learn.org/)**: For providing efficient implementations of Support Vector Machines and other machine learning algorithms.
- **[Matplotlib](https://matplotlib.org/)**: For offering powerful tools for data visualization and plotting.

## Contact

For questions or feedback, please contact rudraxdave.contact@example.com.






