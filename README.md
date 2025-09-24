# n-hexane-rmg-mechanism

This repository contains the RMG input and output files used to construct and validate the optimized kinetic mechanism for n-hexane pyrolysis in a hydrogen plasma reactor, as described in:

> *Numerical Modeling of n-Hexane Pyrolysis with an Optimized Kinetic Mechanism in a Hydrogen Plasma Reactor* (https://arxiv.org/abs/2506.13789)

## Repository Structure

- **RMG/** : Files used for the main numerical modeling study  
  - `input.py` : RMG input script used to generate the mechanism  
  - `output.inp` : Generated mechanism file (reaction kinetics and species data)  
  - `output.html` : HTML summary of the generated mechanism  

- **RMG-test/** : Files used for mechanism validation and testing  
  - `input.py` : Test input script  
  - `output.inp` : Mechanism file generated for validation  
  - `output.html` : HTML summary of the test mechanism  