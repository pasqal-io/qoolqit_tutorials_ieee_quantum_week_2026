# QoolQit tutorial - IEEE Quantum Week 2026
This repository contains the tutorials and exercises for the **IEEE Quantum Week 2026**.
In this README you will find the agenda and the instructions on how to download this repository, install the `qoolqit` library and start programming neutral-atom based QPUs.

# Session 1 — Foundations and Your First Quantum Program
​
**Duration:** 90 minutes  
**Format:** Presentation, discussion, and hands-on tutorial  
​
## Overview
​
This introductory session presents the foundations of analog quantum computing with neutral atoms and introduces QoolQit, PASQAL's software library for developing quantum applications.
​
## Learning objectives
​
By the end of the session, participants will be able to:
​
- Explain the main differences between gate-based and analog quantum computing.
- Describe Rydberg atoms, Rydberg interactions, and the blockade mechanism.
- Identify potential applications of analog quantum computing.
- Understand the role of QoolQit in PASQAL's software ecosystem.
- Apply QoolQit's dimensionless unit convention.
- Describe the compilation workflow.
- Build and run a simple analog quantum program.
​
### 1. Welcome and session overview — 5 min
​
- Session objectives and structure
- Expected outcomes
​
### 2. Introduction and motivation for analog quantum computing — 15 min
​
- What is a Rydberg atom?
- Rydberg interactions
- The Rydberg blockade mechanism
- Gate-based versus analog paradigms
- Analog quantum computing application
​
### 3. Introduction to QoolQit — 20 min
​
- Overview of PASQAL
- PASQAL's software ecosystem
- The role of QoolQit
- Dimensionless unit convention
- Compilation workflow
- Library overview
- Installation and documentation
​
### 4. Hands-on: your first quantum program — 30 min
​
Participants will:
​
1. Import the required QoolQit components.
2. Define a simple neutral-atom register.
3. Configure an analog pulse sequence.
4. Compile the program.
5. Run it using an emulator or an available backend.
6. Inspect and interpret the results.
​
### 5. Recap and questions — 5 min
​
- Review of the key concepts
- Common issues and troubleshooting tips
- Questions and discussion
- Preview of the next session
​
## Prerequisites
​
Participants should have:
​
- Basic familiarity with Python
- A working Python environment
- Access to the tutorial environment or repository
- QoolQit and the required dependencies installed
​
No previous experience with quantum programming is required.
​
## Suggested preparation
​
Before the session:
​
1. Verify that the tutorial environment starts correctly.
2. Confirm that QoolQit can be imported.
3. Download or clone the tutorial materials.
4. Review the installation and documentation links provided by the instructors.
​
---
​
# Session 2 — Combinatorial Optimization with QoolQit
​
**Duration:** 90 minutes  
**Format:** Presentation, live demonstration, and hands-on notebook  
​
## Overview
​
This session introduces combinatorial optimization on analog neutral-atom hardware. Participants will formulate a problem as a QUBO, embed it into an atom register, design and compile an adiabatic quantum program, simulate its execution, and decode the measurement results.
​
## Learning objectives
​
By the end of the session, participants will be able to:
​
- Express a combinatorial optimization problem as a QUBO.
- Explain the relationship between a problem graph, a QUBO matrix, and an atom register.
- Distinguish device-constrained and unconstrained embedding.
- Compare the embedding methods available in QoolQit.
- Design an adiabatic drive using relative timing.
- Compile and simulate an optimization program.
- Decode measurement outcomes and assess solution quality.
- Submit a job to a remote emulator through the PASQAL Cloud platform, subject to access and token availability.
​
### 1. QUBO and embedding — 20 min
​
- Definition of Quadratic Unconstrained Binary Optimization
- Cost function and matrix formulation
- Interpretation of diagonal and off-diagonal terms
- The embedding problem
- Data graph versus atom register
- Device-constrained versus unconstrained embedding
- Live embedding of a small problem.

### 2. Hands-on: writing a quantum optimization program — 40 min
​
Participants work individually on their laptops using a guided notebook. The notebook contains partially empty cells that specify the objects or results to create, following a step-by-step exercise format. The instructors reveal and discuss the solution after each step.

- Step 1 — Define the QUBO
- Step 2 — Embed the problem
- Step 3 — Design and compile the drive
- Step 4 — Execute the program
- Step 5 — Decode the solution
- Step 6 — Explore the parameters
- Step 7 — Access PASQAL Cloud
​
### 3. Outlook, resources, feedback, and Q&A — 15 min
​
- Moving from local simulation to a real QPU
- Beyond combinatorial optimization: Quantum State Preparation
- Contributing to QoolQit and the broader neutral-atom open-source ecosystem
- Open questions
​
### 4. Buffer — 15 min
​
## Prerequisites
​
Participants should have:
​
- Basic familiarity with Python and NumPy
- A working QoolQit environment
- The Session 2 notebook downloaded locally
 
### Clone this repository
```console
git clone https://github.com/pasqal-io/qoolqit_tutorials_ieee_quantum_week_2026.git
