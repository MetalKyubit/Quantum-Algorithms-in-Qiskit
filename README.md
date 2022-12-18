# Quantum-Algorithms-in-Qiskit
Deutsch Jozsa Algorithm, Bernstein Vazirani Algorithm, Grover's Algorithm, Simon's Algorithm 

## 1. DJ Algorithm
The algorithm consists of a function for the quantum circuit of the algorithm and a function that generates the oracle.
#### Input
          Oracle and the number of bits 
Oracle is generated using the function that creates the oracle.
The function generates a quantum circuit for a particular oracle. The quantum circuit is run on a backend and the result is plotted on a histogram.
#### Output 
          If the plot is that all the qubits are 0’s then the function (encoded in the oracle) is constant. If the output is anything other than all 0’s then the function is balanced.

## 2. BV Algorithm
The algorithm consists of a function for the quantum circuit of the algorithm and a function that generates the oracle.
#### Input
          Oracle and the number of bits  Oracle is generated using the function that creates the oracle.
The function generates a quantum circuit for a particular oracle. The quantum circuit is run on a backend and the result is plotted on a histogram.
#### Output 
          The output of the algorithm is the bit string “a” of the function (f(x)= a.x). The state of the qubit finally after the algorithm is run is the bitstring “a”. The histogram plot reads the bit string “a”.

## 3. Simon’s Algorithm
The algorithm consists of a function for the quantum circuit of the algorithm.
#### Input
          Oracle and the number of bits  Oracle is generated using the qiskit built in library for Simon’s oracle.
The function generates a quantum circuit for a particular oracle. The quantum circuit is run on a backend and the result is plotted on a histogram.
#### Output 
          The outputs of the quantum circuit are the y’s for which y.s=0 where s is the secret bit string of the function. The outputs plotted on the histogram represent the y’s which can be further used on a classical computer to find the s using the gaussian elimination method.

## 4. Grovers Algorithm
The algorithm consists of a function for the quantum circuit of the algorithm and a function that generates the oracle.
#### Input
          Oracle and the number of bits  Oracle is generated using the function that creates the oracle.
The function generates a quantum circuit for a particular oracle. The quantum circuit is run on a backend and the result is plotted on a histogram.
#### Output 
          The output of the algorithm is the x for which f(x) = 1. The x can be read from the histogram plot.
