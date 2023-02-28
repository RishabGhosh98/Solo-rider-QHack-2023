# Solo-rider-QHack-2023

Project Name :- VisualEntangle2.0
This is our submission for QHack 2023 hacakthon
Challenge :- Visualisation Challenge
Filaname:- VisualEntangle

Visualisation in QM has never been more important. The days have gone when people were forced to gain insights only from the mathematical perspective.
There are a few ways:-
 1. Quantum correlation Matrix
 2. Quantum entanglement Plot
 3. Density Matrix
 4. Wigner Functions
 5. Husumi distributions
 6. Fock state basis representation

We have used 2 ways to visualise entanglement Quantum Correlation Matrix and Quantum Entanglement plot.
We have taken mainly the above 2 visualisations , as our motivation is to make layman understand how entanglement is working.


In this circuit, we apply a rotation gate (RY) to the first qubit and a phase gate (RZ) to the second qubit, before entangling them with a CNOT gate. 
We then measure the probabilities of measuring each possible state of the two qubits.

The params variable is a list of 100 sets of parameters, each consisting of two values between 0 and pi. 
These parameter values are used to evaluate the circuit for each possible combination of parameter values.

The output of the probs variable should be a list of 100 arrays of length 4, 
representing the probabilities of measuring each possible state of the two qubits (in the computational basis) for each set of parameter values.

The corr_mat variable is a 2x2 correlation matrix that represents the correlations between the two qubits in the quantum state. 
The elements of the matrix represent the probabilities of measuring each possible combination of states for the two qubits. 
For example, the top-left element of the matrix represents the probability of measuring the state |00⟩, while the bottom-right element 
represents the probability of measuring the state |11⟩.

The plt.imshow() command creates the quantum correlation matrix plot, which shows the correlations between the two qubits in the quantum state. 
The plot uses a color scale to represent the probabilities of measuring each possible combination of states, with brighter colors indicating higher probabilities.
The plot also shows how the probabilities change as the parameter values are varied, 
allowing us to explore the behavior of the entangled state in more detail.
