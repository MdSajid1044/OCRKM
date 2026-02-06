# OCRKM - One Class Restricted Kernel Machines


Please cite the following paper if you are using this code. 

A. Quadir, M. Sajid, M. Tanveer (2024). "One Class Restricted Kernel Machines, 31st International Conference on Neural Information Processing (ICONIP), 2024".

Paper Link: https://doi.org/10.1007/978-981-96-6954-7_17

Arxiv Link: https://doi.org/10.48550/arXiv.2502.10443

BibTex
------
```
@inproceedings{Quadir2025OneClassRKM,
  author    = {Quadir, A. and Sajid, Md. and Tanveer, M.},
  title     = {One Class Restricted Kernel Machines},
  booktitle = {Neural Information Processing},
  series    = {Communications in Computer and Information Science},
  pages     = {244–257},
  volume    = {2284},
  year      = {2025},
  publisher = {Springer},
  address   = {Singapore},
  doi       = {10.1007/978-981-96-6954-7_17},
  isbn      = {978-981-96-6954-7}
}
```

The experiments are executed on a computing system running Python 3.11, an Intel(R) Xeon(R) CPU E5-2697 v4 processor operating at 2.30 GHz with 128 GB of Random Access Memory (RAM), and Windows-11.

*Installation*

Our OCRKM implementation requires the following dependencies:

- Python (>=3.7)
- NumPy (>=1.13)
- SciPy

Usage

The following are the best hyperparameters set with respect to the “chess_krvkp” dataset

Regularization Parameter c_1=1, c_2= 1, sig=1

Description of files:

main.py: This is the main file to run selected algorithms on datasets. In the path variable, specify the path to the folder containing the codes and datasets on which you wish to run the algorithm.

One-RKM.py: Solving the optimization problem.

For a comprehensive understanding of the experimental setup, please refer to the paper. Should you encounter any bugs or issues, feel free to contact A. Quadir (mscphd2207141002@iiti.ac.in, abdulquadir19991@gmail.com) or M. Sajid (phd2101241003@iiti.ac.in, sajid.mathml@gmail.com).



