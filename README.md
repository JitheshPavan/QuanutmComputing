# QuanutmComputing</br>
##Deutsch–Jozsa algorithm</br>
![Alt text](/DJA.jpg/?raw=true "Optional Title")
###Intuition
In the picture above, what if there was no oracle? We will get '0' state as the measurement for all the qubits(except the last one). This is the case because Hadamard gate its own unitary. Oracle takes the input |x>|0> and outputs |x>|f(x)>. This is unitary because f_inverse(x) is computable.

All though first x qubits do not change, the fact that they have been entangled with the last qubit changes things. The output is no more 'off' for these qubits. This is due the fact that entanglement causes scalar values to jump around in the tensor product space that has been created. So the point is that entanglement causes change in output. So what if there is no entanglement? This is the case for constant function. The constant function do not depend on x. Therefore, in a sense, there is no entanglement between x and the last qubit. Thereby we get output off(0) for all x qubits. 
