# Computer Laboratory II - Quantum AI

This repository contains all practicals and projects related to *Computer Laboratory-II* for B.E. (Sem-I), Department of Artificial Intelligence and Data Science at DYPIEMR.

## Overview

The aim of this lab course is to develop real-world problem-solving skills using Quantum AI techniques. The course involves working on various algorithms and implementations related to quantum computing, including random number generation, error correction, and quantum teleportation.

## Practical List

1. **[16 Qubit Random Number Generator](./Practical-01/README.md)**
   - *Objective*: Implement a 16 Qubit Random Number Generator using quantum computing principles.
   - *Key Concepts*: Quantum Randomness, Entanglement, Cryptography, AI Randomness.
   - *Language*: Python
   - *Tools*: Qiskit, Jupyter

2. **[Tackle Noise with Error Correction](./Practical-02/README.md)**
   - *Objective*: Implement Quantum Error Correction techniques to handle noise and errors in quantum computing.
   - *Key Concepts*: Quantum Error Correction Codes, Noise Reduction, Quantum Gates.
   - *Language*: Python
   - *Tools*: Qiskit, Jupyter

3. **[Quantum Teleportation Algorithm](./Practical-03/README.md)**
   - *Objective*: Implement the Quantum Teleportation Algorithm in Python.
   - *Key Concepts*: Quantum Teleportation, Entanglement, Classical Communication.
   - *Language*: Python
   - *Tools*: Qiskit, Jupyter

4. **[Randomized Benchmarking Protocol](./Practical-04/README.md)**
   - *Objective*: Implement the Randomized Benchmarking Protocol to assess quantum gate fidelity.
   - *Key Concepts*: Quantum Gate Fidelity, Benchmarking, Clifford Gates.
   - *Language*: Python
   - *Tools*: Qiskit, Jupyter

5. **[5 Qubit Quantum Fourier Transform](./Practical-05/README.md)**
   - *Objective*: Implement a 5 Qubit Quantum Fourier Transform.
   - *Key Concepts*: Quantum Fourier Transform, Shor’s Algorithm, Quantum Phase Estimation.
   - *Language*: Python
   - *Tools*: Qiskit, Jupyter

## Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/Computer-Lab-II.git
   cd Computer-Lab-II
   ```

2. **Install Dependencies**:
   - Ensure you have Python and Jupyter installed.
   - Install Qiskit:
     ```bash
     pip install qiskit
     ```

3. **Run the Practicals**:
   - Navigate to any practical folder and run the Jupyter notebook or Python code provided.

## Contribution

Feel free to fork this repository, open issues, or submit pull requests if you'd like to contribute to improving the lab material or add new functionalities.

## License

This repository is licensed under the MIT License. See [LICENSE](./LICENSE) for more information.
```

### README.md (For each Practical):

Each practical should have a corresponding `README.md` inside its folder, detailing the problem statement, steps, and outputs.

Example for **Practical-01**:

```markdown
# Practical 01: 16 Qubit Random Number Generator

## Objective

The goal of this practical is to implement a 16 Qubit Random Number Generator using quantum computing principles.

## Problem Statement

Create a quantum circuit using Qiskit that implements a random number generator based on the superposition and entanglement of qubits.

## Steps

1. Initialize quantum and classical registers.
2. Create the circuit and apply the Hadamard gate to each qubit.
3. Measure the qubits to generate random numbers.

## Output

Once the program is run, the generated random number will be displayed as a sequence of binary values.

## Usage

To run the code, use the following command:

```bash
python code.py
```

## Example Output

```
Generated Random Number: 1010110010010101
```

## Dependencies
```
- Python
- Qiskit
```