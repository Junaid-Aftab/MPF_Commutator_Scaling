# Multi-Product Formula with Commutator Scaling

This repository contains the numerical computations conducted in support of our paper [Multi-product Hamiltonian Simulation with Explicit Commutator Scaling](https://arxiv.org/abs/2403.08922) by Junaid Aftab, Dong An, and Konstantina Trivisa. <!-- The paper has been submitted for publication in [Communications in Mathematical Physics](https://link.springer.com/journal/220). -->

# Abstract

The well-conditioned multi-product formula (MPF), proposed by [Low, Kliuchnikov, and Wiebe, 2019], is a simple high-order time-independent Hamiltonian simulation algorithm that implements a linear combination of standard product formulas of low order. While the MPF aims to simultaneously exploit commutator scaling among Hamiltonians and achieve near-optimal time and precision dependence, its lack of a rigorous error bound on the nested commutators renders its practical advantage ambiguous. In this work, we conduct a rigorous complexity analysis of the well-conditioned MPF, demonstrating explicit commutator scaling and near-optimal time and precision dependence at the same time. Using our improved complexity analysis, we present several applications of practical interest where the MPF based on a second-order product formula can achieve a polynomial speedup in both system size and evolution time, as well as an exponential speedup in precision, compared to second-order and even higher-order product formulas. Compared to post-Trotter methods, the MPF based on a second-order product formula can achieve polynomially better scaling in system size, with only poly-logarithmic overhead in evolution time and precision.

# Citation

@misc{aftab2024multiproducthamiltoniansimulationexplicit,
  title={Multi-product Hamiltonian simulation with explicit commutator scaling}, 
  author={Junaid Aftab and Dong An and Konstantina Trivisa},
  year={2024},
  eprint={2403.08922},
  archivePrefix={arXiv},
  primaryClass={quant-ph},
  url={https://arxiv.org/abs/2403.08922}, 
}
