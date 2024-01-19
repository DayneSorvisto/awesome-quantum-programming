# Awesome Quantum Programming [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A meticulously curated collection of exceptional quantum programming algorithms, hackathons, tutorials, books, articles, and various resources tailored for quantum programmers.

# Table of Contents
| <!-- -->                                 | <!-- -->                                             |
| ---------------------------------------- | ---------------------------------------------------- |
| [Introduction to Quantum Computing](#introduction-to-quantum-computing) | [Quantum Programming Basics](#quantum-programming-basics) |
| [Quantum Algorithms](#quantum-algorithms) | [Quantum Complexity](#quantum-complexity) |
| [Quantum Programming Languages](#quantum-programming-languages) | [Quantum Programming Tutorials](#quantum-programming-tutorials) |
| [Quantum Programming Hackathons](#quantum-programming-hackathons) | [Books for Learning Quantum Programming](#books-for-learning-quantum-programming) |
| [Articles and Blogs](#articles-and-blogs) | [Quantum Programming Simulators](#quantum-programming-simulators) |
| [Hands-On Exercises](#hands-on-exercises) | [Community and Forums](#community-and-forums) |
| [Online Courses](#online-courses) | 

## Introduction to Quantum Computing Fundamentals

- [Quantum Computing Explained](https://www.ibm.com/quantum-computing/learn/what-is-quantum-computing/): An overview by IBM introducing the fundamental concepts of quantum computing.
- [Qiskit Textbook](https://qiskit.org/textbook/preface.html): A comprehensive textbook by Qiskit, covering the basics of quantum computing and programming using Qiskit, IBM's quantum computing framework.
- [Microsoft Quantum Development Kit](https://learn.microsoft.com/en-us/azure/quantum/): Explore Microsoft's Quantum Development Kit to understand the principles of quantum computing and programming with Q#.
- [Introduction to Quantum Algorithms](https://quantumalgorithmzoo.org/): A collection of quantum algorithms with explanations and implementations for beginners.
- [Awesome Quantum Computing](https://github.com/sindresorhus/awesome-quantum-computing): Check out the Awesome Quantum Computing list on GitHub for a curated collection of resources, tools, and frameworks in the field of quantum computing.

# Quantum Algorithms
<details>
<summary>Click to expand!</summary>

## Overview
- [Quantum Algorithms Overview](https://en.wikipedia.org/wiki/Quantum_algorithm): A comprehensive introduction to quantum algorithms, covering fundamental concepts and their applications.

## Search Algorithms
- [Grover's Algorithm](https://en.wikipedia.org/wiki/Grover%27s_algorithm): Learn about Grover's algorithm, a quantum algorithm for unstructured search that provides a quadratic speedup over classical algorithms.

## Factorization
- [Shor's Algorithm](https://en.wikipedia.org/wiki/Shor%27s_algorithm): Explore Shor's algorithm, a groundbreaking quantum algorithm that efficiently factors large numbers, posing a threat to classical public-key cryptography.

## Quantum Fourier Transform
- [Quantum Fourier Transform](https://en.wikipedia.org/wiki/Quantum_Fourier_transform): Understand the Quantum Fourier Transform, a key component in many quantum algorithms, including Shor's algorithm.

## Variational Quantum Algorithms
- [Variational Quantum Algorithms](https://en.wikipedia.org/wiki/Variational_quantum_algorithm): Delve into variational quantum algorithms, a class of algorithms that use quantum computers to optimize a parameterized quantum circuit for specific tasks.

## Machine Learning
- [Quantum Machine Learning](https://en.wikipedia.org/wiki/Quantum_machine_learning): Explore the intersection of quantum computing and machine learning, including algorithms that leverage quantum parallelism to enhance computational efficiency.

## Quantum Walks
- [Quantum Walks](https://en.wikipedia.org/wiki/Quantum_walk): Learn about quantum walks, a quantum analog to classical random walks, with applications in algorithm design and quantum information processing.

## Adiabatic Quantum Computing
- [Adiabatic Quantum Computing](https://en.wikipedia.org/wiki/Adiabatic_quantum_computation): Understand adiabatic quantum computing, an alternative approach to quantum computation based on the adiabatic theorem.

## Combinatorial Optimization
- [Quantum Approximate Optimization Algorithm (QAOA)](https://en.wikipedia.org/wiki/Quantum_approximate_optimization_algorithm): Explore QAOA, a quantum algorithm designed for combinatorial optimization problems, with applications in various fields.

## Quantum Complexity
- [BQP Complexity Class](https://en.wikipedia.org/wiki/BQP): Learn about the Bounded-error Quantum Polynomial time (BQP) complexity class, which characterizes problems efficiently solvable by a quantum computer.

</details>

## Quantum Programming Frameworks and Languages

<details>
<summary>Qiskit</summary>

- Developed by [IBM](http://www.research.ibm.com/ibm-q/).
- Open-source and widely used.
- Comprehensive suite for quantum computing.
</details>

<details>
<summary>Cirq</summary>

- Developed by [Google](https://quantumai.google/cirq).
- Targets NISQ (Noisy Intermediate-Scale Quantum) devices.
- Focuses on defining and simulating quantum circuits.
</details>

<details>
<summary>Quipper</summary>

- Developed by [Microsoft Research and the University of Oxford](https://www.maths.ox.ac.uk/groups/computational-foundations-computer-science/quantum-computing).
- High-level quantum programming language.
- Emphasizes a functional programming approach.
</details>

<details>
<summary>Q# (Q-sharp)</summary>

- Developed by [Microsoft](https://learn.microsoft.com/en-us/azure/quantum/).
- Part of the Quantum Development Kit.
- Integrates with Visual Studio.
</details>

<details>
<summary>Forest (Rigetti Computing)</summary>

- Includes Quil (Quantum Instruction Language).
- Open-source and part of the [Forest SDK](https://www.rigetti.com/forest).
</details>

<details>
<summary>ProjectQ</summary>

- Open-source framework.
- Enables quantum programming using high-level Python syntax.
- Aims to support various quantum hardware architectures.
</details>

<details>
<summary>Silq</summary>

- Developed by [ETH Zurich](https://silq.ethz.ch/).
- Focuses on improving expressiveness and safety.
- Introduces high-level abstractions.
</details>

<details>
<summary>QDslr</summary>

- Quantum Domain-Specific Language for Rigetti quantum processors.
- Designed to simplify quantum program development.
- Aims to make quantum computing more accessible.
</details>

<details>
<summary>Ocean (D-Wave Systems)</summary>

- Provides tools for quantum annealing.
- D-Wave's quantum processing unit (QPU) is accessed through [Ocean](https://docs.ocean.dwavesys.com/).
</details>

<details>
<summary>XACC (eXtreme-scale ACCelerator)</summary>

- Quantum programming framework.
- Supports various quantum and classical accelerators.
- Aims to provide a hardware-agnostic approach.
</details>

## Quantum Programming Tutorials

<details>
<summary>Introduction to Quantum Computing</summary>

- [Quantum Computing Basics](https://www.ibm.com/quantum-computing/learn/what-is-quantum-computing/)
- [Understanding Qubits and Quantum Gates](https://www.quantum-inspire.com/kbase/qubit-technology/)
- [Quantum Superposition and Entanglement](https://www.scientificamerican.com/article/quantum-superposition-and-entanglement/)
</details>

<details>
<summary>Getting Started with Qiskit</summary>

- [Qiskit Installation Guide](https://qiskit.org/documentation/install.html)
- [Creating Your First Quantum Circuit](https://qiskit.org/documentation/tutorials/circuits/1_getting_started_with_qiskit.html)
- [Simulating Quantum Circuits with Qiskit](https://qiskit.org/documentation/tutorials/circuits/3_simulator_backends.html)
</details>

<details>
<summary>Programming Quantum Algorithms</summary>

- [Implementing Grover's Algorithm](https://quantum-computing.ibm.com/docs/guide/q-algos/grover)
- [Shor's Algorithm and Quantum Factorization](https://www.scottaaronson.com/blog/?p=208)
- [Quantum Machine Learning Basics](https://www.cs.umd.edu/class/fall2020/cmsc657/projects/group_5.pdf)
</details>

<details>
<summary>Microsoft Quantum Development Kit Tutorials</summary>

- [Introduction to Q# Programming](https://learn.microsoft.com/en-us/azure/quantum/quickstarts/1-install-command-line?tabs=tabid-vscode)
- [Quantum Teleportation and Quantum Error Correction](https://learn.microsoft.com/en-us/samples/ms-quantum/samples/)
- [Using Quantum Machine Learning Libraries in Q#](https://learn.microsoft.com/en-us/azure/quantum/optimization)
</details>

<details>
<summary>Google's Cirq Framework Tutorial</summary>

- [Building Quantum Circuits with Cirq](https://quantumai.google/cirq/tutorials)
- [Optimizing Quantum Algorithms for NISQ Devices](https://quantumai.google/cirq/tutorials/educators/nisq-algorithms)
- [Simulating Noisy Intermediate-Scale Quantum (NISQ) Circuits](https://quantumai.google/cirq/simulators)
</details>

<details>
<summary>Quipper Language Learning Path</summary>

- [Introduction to Quipper Programming](https://www.mathstat.dal.ca/~selinger/quipper/)
- [Functional Quantum Programming Concepts](https://www.youtube.com/watch?v=RX1FV_hXw_8)
- [Using Quipper for Quantum Circuit Design](https://arxiv.org/abs/1304.5485)
</details>

<details>
<summary>Forest SDK (Rigetti Computing) Tutorials</summary>

- [Programming Quantum Computers with Quil](https://pyquil-docs.rigetti.com/en/stable/start.html)
- [Hybrid Quantum-Classical Computing with Forest](https://pyquil-docs.rigetti.com/en/stable/wavefunction_simulator.html)
- [Accessing Quantum Cloud Services with Forest](https://www.rigetti.com/forest)
</details>

<details>
<summary>ProjectQ Framework Tutorials</summary>

- [Quantum Programming in Python with ProjectQ](https://projectq.readthedocs.io/en/latest/tutorials.html)
- [High-Level Quantum Abstractions in ProjectQ](https://projectq.readthedocs.io/en/latest/projects/high-level-abstractions.html)
- [Running Quantum Programs on Different Architectures](https://projectq.readthedocs.io/en/latest/projects/architectures.html)
</details>

<details>
<summary>Quantum Machine Learning with Qiskit</summary>

- [Introduction to Quantum Machine Learning](https://qiskit.org/textbook/ch-machine-learning/machine-learning-qiskit-p1.html)
- [Implementing Quantum Neural Networks](https://qiskit.org/textbook/ch-machine-learning/machine-learning-qiskit-p2.html)
- [Quantum Support Vector Machines with Qiskit](https://qiskit.org/textbook/ch-machine-learning/machine-learning-qiskit-p4.html)
</details>

<details>
<summary>Quantum Programming Challenges</summary>

- [Solving Quantum Coding Challenges](https://www.hackerrank.com/domains/tutorials/10-days-of-javascript)
- [Participating in Quantum Hackathons](https://qhack.ai/)
- [Contributing to Open-Source Quantum Projects](https://github.com/topics/quantum-computing)
</details>


## Quantum Programming Hackathons

<details>
<summary>Explore Quantum Challenges and Competitions</summary>

- [IBM Quantum Challenge](https://www.ibm.com/quantum-computing/challenge)
- [Qiskit Hackathon](https://qiskit.org/events/)
- [Microsoft Quantum Challenge](https://learn.microsoft.com/en-us/azure/quantum/quantum-challenge-2022)
</details>

<details>
<summary>Participate in Global Quantum Hackathons</summary>

- [QHack](https://qhack.ai/)
- [Rigetti Quantum Computing Hackathon](https://www.rigetti.com/hackathon)
- [Quantum Open Source Foundation (QOSF) Mentorship Program](https://www.qosf.org/)
</details>

<details>
<summary>Engage in Quantum Computing Competitions</summary>

- [Google Quantum Spring Symposium](https://quantumai.googleblog.com/2022/03/recap-of-google-quantum-spring.html)
- [Quantum Software Challenges](https://www.cioe.cn/en)
- [Quantum Development Challenges on HackerRank](https://www.hackerrank.com/domains/tutorials/10-days-of-javascript)
</details>

<details>
<summary>Join Quantum Programming Communities</summary>

- [Quantum Open Source Foundation (QOSF) Community](https://qosf.org/community/)
- [Quantum Computing Stack Exchange](https://quantum.stackexchange.com/)
- [Qiskit Community Forum](https://quantumcomputing.stackexchange.com/)
</details>


## Books for Learning Quantum Programming

<details>
<summary>Explore Essential Quantum Programming Books</summary>

1. [Quantum Computation and Quantum Information](https://www.amazon.com/Quantum-Computation-Information-Anniversary-Edition/dp/1107002176) by Michael A. Nielsen and Isaac L. Chuang
2. [Quantum Computing: A Gentle Introduction](https://www.amazon.com/Quantum-Computing-Gentle-Introduction/dp/0262539530) by Eleanor G. Rieffel and Wolfgang H. Polak
3. [Programming Quantum Computers: Essential Algorithms and Code Samples](https://www.amazon.com/Programming-Quantum-Computers-Essential-Algorithms/dp/1492039683) by Eric R. Johnston, Nic Harrigan, and Mercedes Gimeno-Segovia
4. [Quantum Computing for Computer Scientists](https://www.amazon.com/Quantum-Computing-Computer-Scientists-Yanofsky/dp/0521879965) by Noson S. Yanofsky and Mirco A. Mannucci
5. [Learn Quantum Computing with Python and Q#](https://www.amazon.com/Learn-Quantum-Computing-Python-Q/dp/1484273285) by Sarah C. Kaiser and Chris Granade
</details>

## Articles and Blogs

<details>
<summary>Read Insightful Articles and Blogs on Quantum Programming</summary>

1. [Quantum Programming: Getting Started with the Basics](https://www.ibm.com/cloud/learn/quantum-programming-basics)
2. [The Quantum Quest: Top Blogs on Quantum Computing](https://medium.com/swlh/the-quantum-quest-top-blogs-on-quantum-computing-5f67da163fa3)
3. [Microsoft Quantum Blog](https://www.microsoft.com/en-us/quantum/blog/)
4. [Qiskit Blog](https://www.ibm.com/cloud/learn/quantum-programming-basics)
5. [Quantum Computing Report](https://quantumcomputingreport.com/)
</details>

## Quantum Programming Simulators

<details>
<summary>Explore Quantum Programming Simulators</summary>

1. [IBM Quantum Experience](https://www.ibm.com/quantum-computing/)
2. [Microsoft Quantum Development Kit](https://www.microsoft.com/en-us/quantum/development-kit)
3. [Qiskit](https://qiskit.org/)
4. [Rigetti Forest](https://rigetti.com/forest)
5. [Google Cirq](https://quantumai.google/cirq)
</details>

## Quantum Programming for Developers

<details>
<summary>Explore Quantum Programming Resources for Developers</summary>

### Hands-On Exercises

1. [IBM Quantum Experience - Programming Exercises](https://www.ibm.com/quantum-computing/)
2. [Microsoft Quantum Katas](https://learn.microsoft.com/en-us/azure/quantum/)
3. [Qiskit Tutorials](https://qiskit.org/documentation/tutorials/)

### Community and Forums

1. [Quantum Computing Stack Exchange](https://quantum.stackexchange.com/)
2. [IBM Quantum Community](https://quantum-computing.ibm.com/docs/collaborative/)
3. [Qiskit Community](https://qiskit.org/community)

### Online Courses

1. [edX - Quantum Machine Learning](https://www.edx.org/professional-certificate/quantum-machine-learning)
2. [Coursera - Quantum Computing for Developers](https://www.coursera.org/learn/quantum-computing-for-developers)
3. [Udacity - Introduction to Quantum Computing](https://www.udacity.com/course/intro-to-quantum-computing--nd220)
</details>

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
