# Bayesian item response theory (IRT) implemented with pystan and numpyro
This repository includes source code of our paper (Usefulness of pystan and numpyro in Bayesian item response theory).

In the source code, Bayesian IRT models (1PL-IRT and 2PL-IRT) are implemented with pystan and numpyro.
In our paper, the estimation results of the latent parameters of 1PL-IRT and 2PL-IRT were compared between pystan and numpyro using the source code of this repository. 


# Requirement
The source code is described as ipynb (notebook) file. 
In our paper, Google Colaboratory was used to run the experiments. 

The following software packages were used on Google Colaboratory.

* pystan, version 3.3.0
* jax, version 0.4.4
* jaxlib, version 0.4.4+cuda11.cudnn82
* numpyro, version 0.10.1


# Author of source code
The source code of this repository is written by the following authors.

* Mizuho Nishio (Kobe University and Kyoto University)
* Eiji Ota (Futaba Numerical Technologies) 


# Paper
If the source code of this repository is used, please cite the following papers.

## Journal paper
Nishio M, Ota E, Matsuo H, Matsunaga T, Miyazaki A, Murakami T. 2023. Comparison between pystan and numpyro in Bayesian item response theory: evaluation of agreement of estimated latent parameters and sampling performance. PeerJ Computer Science 9:e1620 

* DOI: https://doi.org/10.7717/peerj-cs.1620
* URL: https://peerj.com/articles/cs-1620/

## Preprint paper

* DOI: https://doi.org/10.1101/2023.03.29.23287903
* URL: https://medrxiv.org/cgi/content/short/2023.03.29.23287903v1


# License
The source code of this repository is licensed under MIT license. For the detail, please see License file of this repository.

