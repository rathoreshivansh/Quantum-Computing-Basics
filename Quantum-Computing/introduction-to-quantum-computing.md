# Classical Bit and Introduction to Quantum Bit

## Classical Bit

In our previous session, we had a discussion about quantum mechanics. We explored the concepts and the theories related to quantum mechanics. Now, we will dive into understanding what a quantum bit (qubit) is and how it's different from the classical logical bit.

A **classical bit** is the fundamental unit of information used in classical, conventional computing. It can only have two states:
- **On** (represented by 1)
- **Off** (represented by 0)

These two states form the basis for all modern computing devices, including computers, mobile phones, supercomputers, servers, and even basic calculators. By combining these 1s and 0s in different sequences, modern systems can process complex information.

### How a Classical Bit Works

To represent these states physically, **transistors** are used. A transistor is an electronic switch that can control the flow of current in a circuit. If a voltage is applied to the base of the transistor, current will flow; if the voltage is removed, the current stops. This mechanism allows transistors to act as the building blocks for digital circuits, which are the foundation of logic gates and ultimately processors.

Transistors are small components made from semiconductors, and their size allows them to be embedded in circuits on a very small scale, enabling the miniaturization of modern electronic devices.

### Classical Bit Representation

In classical computing, **every piece of data**—whether text, images, videos, or sounds—is represented as binary digits (1s and 0s). For example:
- The word "high" can be converted into its ASCII code, and then those codes are converted into binary digits.
- Similarly, images or videos can be stored as long sequences of binary numbers.

In fact, even analog signals (like sound waves) are converted into digital form using a **Digital Signal Processor (DSP)**. These digital signals are stored in memory and can later be processed or converted back to analog form to be played through speakers.

This is how **binary processing** works in computers: everything is converted into binary digits (bits), processed, and then output.

# Introduction to Quantum Bit (Qubit)

**Quantum Bit (Qubit)**.

A **quantum bit**, or **qubit**, is the basic unit of quantum information. Just like a classical bit, a qubit can also exist in two states: **0** and **1**. However, there is a key difference: thanks to a phenomenon called **superposition**, a qubit can exist in both states at the same time. This property allows qubits to perform complex calculations much faster than classical bits.

### Superposition in Qubits

A classical bit can only be in one state at a time — either 0 or 1. In contrast, a **qubit** can exist in **both states at the same time** due to the principle of superposition, which we discussed earlier. This unique property of a quantum particle allows it to be in a superposition of **both 0 and 1** simultaneously.

Whenever a qubit is observed, it collapses into one of these states based on probability. This behavior makes qubits far more powerful than classical bits for certain computations.

### The Number of Possible States

In our previous session, we saw that a classical bit has two possible states (0 and 1). Similarly, a qubit can have two states: 0 or 1. However, the difference lies in the fact that, because of superposition, multiple qubits can represent many more possible states simultaneously.

- **1 qubit**: Can represent both 0 and 1 at the same time.
- **2 qubits**: Can represent 4 states at the same time (00, 01, 10, 11).
- **3 qubits**: Can represent 8 states at the same time.
- **10 qubits**: Can represent 1024 states at the same time.

This exponential growth in the number of possible states with the addition of each qubit gives quantum computers a massive advantage over classical computers in solving certain types of problems.

### Qubits and Parallel Processing

This feature of qubits — the ability to exist in multiple states at the same time — allows quantum computers to perform tasks in **parallel**. For example:
- **Multiple database searches** can be done simultaneously.
- **Artificial intelligence** (AI) tasks like **deep learning** can be accelerated using quantum parallelism.

In classical computing, if you are trying to solve a problem like navigating through a maze, you would need to go through each possible option one by one until you find the right path. In contrast, with qubits, you can explore all possible paths at once due to superposition.

# Creating a Quantum Qubit

## Introduction

Just as a classical bit is created using a **transistor**, which controls the flow of electricity or electrons, a **quantum bit (qubit)** is created using the **spin of an electron** or the **orientation of a photon**. In classical computing, the flow of electrons determines the value of a bit. In quantum computing, however, the state of a qubit is determined by properties like the **spin of an electron** or the **polarization of a photon**.

### Classical vs Quantum Bit Creation

- **Classical bit**: The state of a bit is determined by the flow of electricity or electrons.
- **Quantum bit (qubit)**: The state of a qubit is determined by either:
  - **The spin of an electron** (electron spin)
  - **The orientation of a photon** (photon polarization)

### Electron Spin as a Qubit

Consider an individual **electron** in an atom. Electrons have a property called **spin**, which can have two possible states:
- **Spin-down**: Represented as **0** (off state).
- **Spin-up**: Represented as **1** (on state).

However, electrons are very sensitive to their surroundings, and at room temperature, they tend to vibrate due to thermal energy. This makes it impossible to precisely control their spin for quantum computing.

### Cooling to Absolute Zero

To overcome this problem, scientists **cool the system to extremely low temperatures** (close to **absolute zero**). At near absolute zero temperature (around **15 millikelvin**), the electrons have minimal energy and remain stable in a fixed state without vibrating. This is when quantum systems can be controlled with precision.

### Quantum Qubit Processor

Quantum computers need special equipment to create and manipulate qubits. This setup typically includes a **quantum qubit processor** housed in a special fridge-like apparatus that decreases the temperature to near absolute zero. As the temperature drops, the quantum processor stabilizes the electron spins in a controlled state, ready for manipulation.

- **Low energy state**: The electron is in the **spin-down** state (0).
- **Microwave energy**: To flip the electron from spin-down (0) to spin-up (1), we use **microwaves** that provide the energy necessary to flip the electron. This process is not as simple as flipping a switch. Instead, the electron must be carefully manipulated to move through the energy levels to achieve the desired state.

### Flipping the Qubit

Using precision microwave signals, scientists can flip a qubit from **0 to 1** or from **1 to 0** by adding energy to the electron spin. However, this flip requires passing through intermediate energy states. The process is delicate and requires precision to ensure the correct state is achieved.

# Quantum Qubit Representation and Dirac Notation

## Introduction to Qubit Representation

In classical computing, representing a bit is straightforward: it can either be **0** or **1**. This is achieved by using an **on/off** state of a switch — **on** represents **1**, and **off** represents **0**.

However, in quantum computing, **representing a qubit** is a bit more complex. A qubit doesn’t simply have an on/off state like a classical bit. Instead, a qubit’s state is represented by the **spin position of an electron** or the **polarization of a photon**. This concept is very different from classical bits, as the qubit can exist in a **superposition** of states, rather than being strictly 0 or 1.

### Electron Spin and Energy States

Let's take the example of an **electron spin** to represent the state of a qubit. The electron can be in one of two states:

- **Low Energy State (0)**: The electron is pointing downward (spin-down state).
- **High Energy State (1)**: The electron is pointing upward (spin-up state).

Initially, the electron might be in a low energy state (state 0). When we apply an **electromagnetic wave**, such as a microwave, the electron spins and moves to a higher energy state. As more energy is applied, the electron will continue to rotate in space.

This phenomenon is not represented in a linear two-dimensional space but rather in a **three-dimensional spherical space** known as the **Bloch Sphere**.

### The Bloch Sphere

The **Bloch Sphere** is a conceptual model that represents the state of a qubit. The two key points on this sphere are:
- **0 state (spin-down)**: Represented as the **south pole** of the sphere.
- **1 state (spin-up)**: Represented as the **north pole** of the sphere.

In reality, the qubit doesn’t necessarily sit precisely on these poles. Due to the **superposition** nature of quantum mechanics, the qubit can exist **anywhere on the surface of the Bloch Sphere**, depending on the energy applied to the electron.

### Superposition and Quantum State

A qubit can be in a **superposition** of states, meaning it can have some probability of being in state 0 (spin-down) and some probability of being in state 1 (spin-up) at the same time. This is the essence of **quantum superposition**.

For example:
- If the electron is more likely to be found in state 1 (spin-up), we might say that the probability of measuring the qubit as **1** is **60%**, and the probability of measuring it as **0** (spin-down) is **40%**.
- We can represent this superposition with the following **Dirac notation**:

|ψ⟩ = α|0⟩ + β|1⟩


Where:
- **|ψ⟩** represents the quantum state of the qubit.
- **|0⟩** and **|1⟩** represent the **spin-down (0)** and **spin-up (1)** states, respectively.
- **α** and **β** are complex numbers representing the probability amplitudes. The square of the magnitude of these coefficients gives the probability of measuring the qubit in a specific state.

In our case, for a 60% chance of being in state 1 and a 40% chance of being in state 0, we would write:

|ψ⟩ = 0.4|0⟩ + 0.6|1⟩


Where:
- **0.4** corresponds to the **40% probability** of being in state 0.
- **0.6** corresponds to the **60% probability** of being in state 1.

### Measurement and Collapse

Although a qubit exists in a superposition of states, when we measure it, the **wavefunction collapses**. This means the qubit will "choose" one of the possible states, and we’ll observe either **0** or **1** based on the probabilities we defined earlier.

If we measure the qubit, there is a higher chance (60%) that it will collapse into state 1, but there’s also a 40% chance it will collapse into state 0.



