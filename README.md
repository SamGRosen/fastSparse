# fastSparse

This repository contains source code to our AISTATS 2022 paper: 

* [Fast Sparse Classification for Generalized Linear and Additive Models](https://arxiv.org/abs/2202.11389)

Acknowledgement: For this AISTATS camera ready code repository, we build our method based on [L0Learn](https://github.com/hazimehh/L0Learn#l0learn-fast-best-subset-selection)’s codebase, so that we could use its preprocessing steps, and the pipeline for running the full regularization path of $λ_0$ values. Therefore, the computational speedup shown in our paper solely comes from our new proposed algorithms.

We plan to build our own pipeline and further extend this work before pushing the project to CRAN. Right now you can install the project from GitHub directly. Our repository will be actively maintained, and the most updated version can be found at this current GitHub page.

If you encounter any problem with installation or usage, please don't hesitate to reach out to the following email address: jiachang.liu@duke.edu.

---
## 1. Installation ##

To install this R package, please go the [installation folder](./installation) and follow the installation instructions.

---
## 2. Application and Usage
We provide a toolkit for producing sparse and interpretable generalized linear and additive models for the binary classiciation task by solving the L0-regularized problems. The classiciation loss can be either the logistic loss or the exponential loss. The algorithms can produce high quality (swap 1-OPT) solutions and are generally 2 to 5 times faster than previous approaches.

To understand how to use this R package, please go the [application and usage folder](./application_and_usage).



## 3. Experiment Replication
To replicate our experimental results shown in the paper, please go the [experiments folder](./experiments).

## 4. Step Function Visualization
To reproduce the step function plots shown in the paper, please go the [visualization folder](./visualization).

## Citing Our Work ##
If you find our work useful in your research, please consider citing the following paper:

```
@inproceedings{liu2022fast,
  title={Fast Sparse Classification for Generalized Linear and Additive Models},
  author={Liu, Jiachang and Zhong, Chudi and Seltzer, Margo and Rudin, Cynthia},
  booktitle={International Conference on Artificial Intelligence and Statistics},
  pages={9304--9333},
  year={2022},
  organization={PMLR}
}