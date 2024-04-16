# MATLAB Model of the Lac Operon

## Overview
This repository contains a MATLAB project designed to model the regulatory behavior of the lac operon in bacteria, particularly E. coli. The lac operon is a classic example of gene regulation and is essential for the metabolism of lactose when glucose is not present. The model simulates interactions between the operon, the Lac repressor (LacI), and the inducer molecule allolactose, providing insights into the dynamics of gene expression under different biochemical conditions.

## Project Description
The lac operon model includes components such as the operon itself (gop), the repressor protein (lacI), the inducer molecule allolactose (alac), and the complexes formed between these molecules. The model uses differential equations to simulate the binding dynamics and predict how changes in lactose availability affect gene expression. This project was created as part of a mini-project for SysMIC, conducted at University College London.

## Features
- **Simulation of Lac Operon Dynamics**: The model uses reversible reactions and differential equations to simulate the interaction between the lac operon components.
- **Behavior Analysis Under Different Conditions**: By altering initial conditions and parameters, users can explore how the lac operon responds to changes in lactose and allolactose concentrations.
- **MATLAB Scripts for Modeling**: All scripts are written in MATLAB, ensuring that the simulations can be run in an environment familiar to many scientists and engineers.

## Installation
1. **MATLAB Requirement**: Ensure you have MATLAB installed on your computer. The project is compatible with MATLAB 2020a and later versions.
2. **Download Repository**: Clone or download this repository to your local machine.

## Usage
Open MATLAB and navigate to the directory where you have cloned or downloaded the repository. Open the project files and run them directly in MATLAB:
1. **Open the Main Script**: Locate the main script that initializes the model parameters and starts the simulation.
2. **Run the Simulation**: Execute the script to start the simulation. You can modify the initial conditions or parameters within the script to see how they affect the behavior of the operon.
3. **Analyze Results**: The output will include graphs and data that illustrate the dynamics of the lac operon under various conditions. Analyze these results to gain insights into the operon's behavior.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for more details.

## Author
- **Christos Efthymiou** - Initial work and development.

## Acknowledgments
- Thanks to SysMIC and University College London for providing the educational platform for this project.
- Appreciation to the foundational research by Jacob and Monod, which underpins the biological understanding implemented in this model.