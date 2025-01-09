# Qubit Representation using Vectors and Matrices

## Scalars vs Vectors
In physics, there are two ways to represent quantities: **scalars** and **vectors**.
- **Scalars** only require a magnitude to describe the quantity. Examples include:
  - Length (e.g., 5 cm)
  - Mass
  - Temperature

- **Vectors** require both magnitude and direction to describe the quantity. For example:
  - Displacement: "5 cm to the left" (this includes both magnitude and direction).
  
In quantum mechanics, the **spin direction** of particles like electrons can be considered as a vector, where we need both magnitude and direction to describe the spin.

## Quantum State Representation
We use vectors to represent the quantum state of a qubit. For example, an electron's spin can be represented as a quantum state with a specific direction. This spin can be:
- **Up spin** (classical) represented as |0⟩.
- **Down spin** (classical) represented as |1⟩.

In the **superposition** state, the spin of the electron can be in any direction within the **Bloch sphere**. This requires both magnitude and direction to describe.

## Notation and Matrix Representation
The **bracket notation** (also called **Dirac notation**) can be used to describe quantum states, such as:
- **|0⟩** for spin up
- **|1⟩** for spin down

However, when dealing with quantum states in **superposition**, it is difficult to perform calculations using just the bracket notation. To calculate the quantum state, we convert the notation into a **matrix** representation.

### Matrix Representation of Qubits
A quantum state such as **|0⟩** (spin up) can be represented as a matrix:
| 1 |
| 0 |
This is a 2x1 matrix.

Similarly, |1⟩ (spin down) can be represented as:

| 0 |
| 1 |
By representing the quantum state in matrix form, we can easily perform calculations, especially when dealing with operations like the dot product (matrix multiplication).

# Matrix Multiplication
In order to perform matrix multiplication (dot product), the number of columns in the first matrix should match the number of rows in the second matrix. For example, if we have two matrices A and B:

Matrix A:
| A | B |
| C | D |

Matrix B:
| E | F |

The multiplication of these matrices will be:

| A*E + B*G | A*F + B*H |

The resulting matrix will have dimensions matching the rules of matrix multiplication. We'll use this kind of matrix calculation when working with quantum gates in future sessions.

