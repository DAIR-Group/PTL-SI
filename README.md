# PTL-SI: Post-Transfer Learning Statistical Inference in High-Dimensional Regression
**PTL-SI** is a Python package designed for conducting valid statistical inference in high-dimensional regression (HDR) settings with transfer learning (TL). It implements selective inference methods to control the false positive rate (FPR) while maximizing the true positive rate (TPR) in feature selection after transfer learning.


## Requirements & Installation
This package has the following requirements:
- **[numpy](https://numpy.org/doc/stable/)**
- **[mpmath](https://mpmath.org/)** 
- **[skglm](https://contrib.scikit-learn.org/skglm/)**
- **[scipy](https://docs.scipy.org/doc/)** 
- **[matplotlib](https://matplotlib.org/)** 
- **[statsmodels](https://www.statsmodels.org/stable/index.html)**


This package can be installed using pip:
```bash
pip install ptl_si
```

We recommend to install or update anaconda to the latest version and use Python 3 (We used Python 3.11.4).

## Example Notebooks
We provide several Jupyter notebooks demonstrating how to use the `ptl_si` package in our `examples/` directory:

  - `ex1_p_value_TF.ipynb` - Example for computing p-value for TransFusion
  - `ex2_p_value_OTL.ipynb` -  Example for computing p-value for Oracle Trans-Lasso
  - `ex3_pivot.ipynb` - Check the uniformity of the pivot
