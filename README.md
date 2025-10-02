# Quantum Amplitude Estimation for Monte Carlo Integration <br>
## Overview <br>
This project demonstrates the implementation of Quantum Amplitude Estimation (QAE) to accelerate Monte Carlo (MC) integration. <br>
We implemented a quantum circuit to integrate the function $sin^2(x)$ and validated the theoretical
speedup of QAE compared to classical Monte Carlo. <br>
Our results show that QAE achieves faster error reduction, requires fewer samples, and provides insights into real-device noise effects. <br>

## Key Result <br>
* Implemented a quantum circuit to integrate $sin^2$ using the Monte Carlo method. <br>
* As theory predicts: QAE reduces error faster than classical MC ($O(\tfrac{1}{N})$ vs $O(\tfrac{1}{\sqrt{N}})$). <br>
* More efficient: Achieved the same accuracy with ~10× fewer shots. <br>
* Estimated probability distributions using characteristic functions with Quantum Monte Carlo. <br>
