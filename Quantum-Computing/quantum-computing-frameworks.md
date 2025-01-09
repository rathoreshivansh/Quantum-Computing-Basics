# Quantum Computing Frameworks and Companies

## Introduction
In the previous session, we discussed classical logic gates, and now we're moving on to quantum logic gates. But before we dive into quantum gates, let's first explore the frameworks and tools used by popular companies in the field of quantum computing. These frameworks are designed to help us understand and build quantum algorithms, and many of them have made quantum computing more accessible for learning.

## Popular Companies and Their Quantum Computing Frameworks

### 1. **Google - CIRQ**
Google has developed a quantum computing framework called **Cirq**. The name "Cirq" is derived from **Quantum Circuit** (`C` for circuit and `Q` for quantum). Cirq is used for developing quantum circuits and running them on quantum simulators and real quantum computers. However, as of the latest updates, **Cirq** is primarily available for **quantum simulation** rather than operating real-time quantum computers.

- **Features**:
  - Develop quantum circuits.
  - Run simulations on quantum computers.
  - No dedicated website, but Cirq documentation and tutorials can be found at: [Cirq on ReadTheDocs](https://cirq.readthedocs.io)

### 2. **TensorFlow Quantum (TFQ)**
TensorFlow Quantum is a framework that combines quantum computing and machine learning, specifically designed for building quantum machine learning models. It is based on **Cirq** and is aimed at developing **Quantum Convolutional Neural Networks (QCNN)** or **Quantum Neural Networks (QNN)**. TensorFlow Quantum allows users to apply machine learning techniques to quantum computing, offering a hybrid model for AI and quantum research.

- **Use Cases**:
  - Quantum Convolutional Neural Networks (QCNN).
  - Hybrid models of quantum computing and AI for research.

### 3. **Microsoft - Quantum Development Kit and Q#**
Microsoft offers the **Quantum Development Kit (QDK)** and **Q#**, a high-level programming language for quantum computing. Q# is similar to Microsoft's C# and is designed to be interoperable with **Python**. The **Azure Quantum** platform provided by Microsoft allows users to run quantum circuits on actual quantum hardware in the cloud, making quantum computing accessible over the internet.

- **Features**:
  - **Q#** language: High-level programming language for quantum computing.
  - **Microsoft Azure Quantum**: Cloud platform for quantum computing.
  - Interoperability with **Python**.

### 4. **IBM - Qiskit**
IBM’s **Qiskit** is one of the most popular and easy-to-learn quantum computing frameworks. It is based on Python and follows a "learn by viewing" method, making it beginner-friendly. With Qiskit, users can develop quantum circuits and run them on their **local simulators** or, by registering with IBM’s **IBM Q Experience**, run them on actual IBM quantum computers via the cloud.

- **Features**:
  - Python-based framework.
  - Quantum circuits can be executed on local simulators or actual IBM quantum hardware.
  - Available for free to use on **IBM Q Experience** (via the cloud).
  - Widely used in **hackathons**, **competitions**, **universities**, and **research facilities** worldwide.

- **Learning Resources**:
  - Official home page: [Qiskit](https://qiskit.org)
  - Includes links to documentation, tutorials, and community support.

---

## Conclusion
These frameworks from Google, Microsoft, and IBM are paving the way for quantum computing, each providing unique features suited for different use cases. If you’re a beginner, **Qiskit** is highly recommended due to its simplicity and ease of learning. In the next session, we will install Qiskit on our local computer and explore how we can run quantum circuits on real quantum hardware via IBM's cloud platform.

Stay tuned for the next session, where we'll get hands-on with Qiskit!

