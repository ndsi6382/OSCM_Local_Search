# Local Search Methods for the One-Sided Crossing Minimisation Problem

This repository contains the code for *Local Search Methods for the One-Sided Crossing Minimisation Problem*, available [here](https://drive.proton.me/urls/ZZ4GWWQJXM#5890rmTgPpJT). All code has been implemented within Jupyter Notebooks with SageMath 9.5 kernels and Python 3.10. Each notebook is self-contained.

 - `OSCM_Introduction.ipynb` contains a brief introduction to the One-Sided Crossing Minimisation Problem.
 - `OSCM_Local_Search.ipynb` contains the presented algorithms.
 - `data` contains test instances for the provided code.

References:

- The base graph class used throughout the project is a heavily modified version of the class used in the [PACE Challenge verifier](https://pypi.org/project/pace2024-verifier/) package.
- Outside of standard library modules for Python and SageMath, the [segment-tree](https://github.com/evgeth/segment_tree) package is required. This may be installed by running `sage --pip install segment-tree`.

---

This project is licensed under the MIT License - see the [LICENSE](https://github.com/ndsi6382/OSCM_Local_Search/blob/main/LICENSE) file for details.