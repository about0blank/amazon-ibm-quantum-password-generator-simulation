Quantum Password Generator
Purpose
This repository contains a Python application designed to showcase the integration of quantum computing into cybersecurity, specifically for generating cryptographically secure passwords. The application utilizes quantum processing units (QPUs) from two leading platforms: Amazon Braket's Aquila and IBM Quantum. These platforms provide the quantum randomness needed to enhance the cryptographic strength of the generated passwords.

Key Features
Quantum-Enhanced Security: Leverages genuine quantum randomness from both Amazon Braket's Aquila and IBM Quantum for password generation.
High Entropy Passwords: Capable of generating complex passwords that are suitable for securing high-stakes data and systems.
Multi-Platform Integration: Demonstrates how to interact with different quantum computing services to achieve a common cybersecurity goal.
How It Works
The application engages with the selected quantum computing service to initiate a quantum task. This task generates a set of quantum random numbers based on the measurement of qubits' states. These quantum random numbers then feed into the Python secrets library, which is responsible for generating a cryptographically secure password.

Getting Started
To use this application, you will need:

Access to Amazon Braket and/or IBM Quantum.
Python installed on your machine with the secrets library.
Configuration set up to communicate with the chosen quantum services.
Detailed instructions on setting up and running the application with either Amazon Braket or IBM Quantum are provided in the subsequent sections of this README
