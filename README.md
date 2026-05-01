# Emerging Technologies - Assessment Problem set

This repository contains a Jupyter notebook implementing quantum computing algorithms using Qiskit, focusing on the Deutsch-Jozsa algorithm. The problems explore the difference between quantum and classical algorithms. 

## Purpose

The project demonstrates the quantum advantage through the Deutsch-Jozsa algorithm, which can determine if a function is constant or balanced with a single query, compared to the classical approach requiring up to 2^(n-1) + 1 evaluations in the worst case.

## Problems Covered

1. **Generating Random Boolean Functions** - Creates random constant and balanced oracle functions with 4-bit inputs
2. **Classical Testing for Function Type** - Implements deterministic classical algorithm for comparison
3. **Quantum Oracles** - Builds quantum circuits that encode classical functions
4. **Deutsch's Algorithm** - Implements the original 1-bit Deutsch algorithm
5. **Scaling to Deutsch-Jozsa Algorithm** - Extends to 4-bit functions using Qiskit

## Setup Instructions

### Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd emerging-technologies
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

### Running the Notebook

Launch Jupyter and open the notebook:

```bash
jupyter lab 
```

## Usage

Execute the cells in order to:
- Generate random Boolean functions (constant and balanced)
- Test classical vs quantum approaches
- Visualize quantum circuits
- Observe quantum speedup with the Deutsch-Jozsa algorithm

## Key Concepts

- **Constant Function**: Returns the same output (True/False) for all inputs
- **Balanced Function**: Returns True for exactly half of all possible inputs
- **Oracle**: A "black box" function that can be queried but not inspected
- **Phase Kickback**: Quantum phenomenon where the ancilla qubit's state affects the input qubits
- **Quantum Superposition**: Allows evaluating all inputs simultaneously
