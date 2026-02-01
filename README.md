# Quantum Amplitude Estimation for Value at Risk

## Description
This work is performed by (Asymptotically) Free Qubits for the [iQuHACK2026 State Street x Classiq Challenge](https://github.com/iQuHACK/2026-State-Street-Classiq/blob/main/README.md). The Value at Risk (VaR) is calculated using classical Monte Carlo and different quantum methods, including the conventional Quantum Amplitude Estimation (QAE), Iterative Quantum Amplitude Estimation (IQAE), and an adaptive, IQAE-inspired method.

1. Classical simulations are done for the Gaussian distribution using "Classical_Tasks.ipynb", and for the fat-tail.

2. Quantum encoding of the problem, Quantum Amplitude Estimation Algorithm, and basic implementation of Iterative Quantum Amplitude Estimation are given in "VaR_Estimation_QAE.ipynb".

3. More in-depth error and scaling analyses are provided in "Classical_Tasks_tail_distribution.ipynb" and "IQAE_VaR_estimation_normal_distr.ipynb".

4. Adaptive Quantum Amplitude Estimation Algorithm using gradient descent to optimize the number of queries is given in "Adaptive_IQAE.ipynb".

For more information, see the [pdf file](https://github.com/tanxnguyen/-Asymptotically-Free-Qubits-iQuHACK2026/blob/main/iQuHack.pdf).




