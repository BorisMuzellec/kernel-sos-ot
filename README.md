# Kernel Sum-of-Squares Estimators for Smooth Optimal Transport

## Overview

This repository complements the paper ["A Dimension-free Computational Upper Bound for Smooth Optimal Transport Estimation"](https://arxiv.org/abs/2101.05380) (Vacher A., Muzellec B., Rudi A., Bach F., Vialard F.X.):

- `optim.py` implements the interior point method described therein;
- `utils.py` contains methods of general utility such as kernel functions and optimal transport functions.
- `sobol_seq.py` and `sobol.cpp` implement Sobol quasi-random sequences. Original code is available from http://people.sc.fsu.edu/~jburkardt/py_src/sobol/sobol.html.

An example notebook is also available: `1D Example.ipynb`.
## References

Vacher A., Muzellec B., Rudi A., Bach F., Vialard F.X.: [A Dimension-free Computational Upper Bound for Smooth Optimal Transport Estimation](https://arxiv.org/abs/2101.05380).

```
@article{vacher2021dimension,
  title={A Dimension-free Computational Upper-bound for Smooth Optimal Transport Estimation},
  author={Vacher, Adrien and Muzellec, Boris and Rudi, Alessandro and Bach, Francis and Vialard, Francois-Xavier},
  booktitle={Conference on Learning Theory},
  year={2021}
}
```

## Dependencies
- Python 3+
- Numpy
- [POT](https://pot.readthedocs.io/en/stable/) (for the example notebook only).
