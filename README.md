--- 2019 Qiskit Camp ---

This project contains a different optimization method for UCCSD calculation.

In our method, only part of the all parameters will be optimized (using COBYLA method, by default) at one time. Then this procedure repeats for other pairs of parameters. With this manner, one does not have to optimize all parameters at once, which improves the efficiency of UCCSD.


