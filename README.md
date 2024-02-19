# QuanutmComputing</br>
# Deutsch–Jozsa algorithm</br>
![Alt text](pictures/DJA.jpg/?raw=true "DJA")</br>
### Intuition</br>
In the picture given above, if there were no oracle, the measurement for all qubits (except the last one) would result in the '0' state. This is because the Hadamard gate is its own unitary, and the oracle, which takes the input |x>|0> and outputs |x>|f(x)>, is also unitary due to the computability of f_inverse(x).
</br>
</br>
Although the first x qubits do not change, the entanglement with the last qubit alters the output. Entanglement causes scalar values to jump around in the tensor product space that has been created. The key point is that entanglement induces a change in the output. However, in the case of a constant function, where the function does not depend on x, there is, in a sense, no entanglement between x and the last qubit. Consequently, the output for all x qubits is 'off' (0).
</br>
Balanced function introduces a relative phase of -1. The entanglement ensures that all off-state is not recovered.
###Computational Complexity
In classical computing, it is necessary to check the outputs for half of the inputs, resulting in a complexity of 2^(N-1) + 1. This leads to exponential growth. However, in quantum computing, only n+1 qubits are needed. This reduction transforms an exponential problem into a polynomial one, placing it in the polynomial complexity (P) group.
