# QuanutmComputing</br>
# Deutsch–Jozsa algorithm</br>
![Alt text](Pictures/DJA.jpg/?raw=true "DJA")</br>
### Intuition</br>
In the given scenario, if there were no oracle, the measurement for all qubits (except the last one) would result in the '0' state. This is because the Hadamard gate is its own unitary, and the oracle, which takes the input |x>|0> and outputs |x>|f(x)>, is also unitary due to the computability of f_inverse(x).
</br>
</br>
Although the first x qubits do not change, the entanglement with the last qubit alters the output. Entanglement causes scalar values to jump around in the tensor product space that has been created. The key point is that entanglement induces a change in the output. However, in the case of a constant function, where the function does not depend on x, there is, in a sense, no entanglement between x and the last qubit. Consequently, the output for all x qubits is 'off' (0).
</br>
