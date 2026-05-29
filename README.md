
<h1 align="center">
Towards a Shared Embodied Intelligence of Humanoid Robots: Optimization, Development, and Testing of the Human-Aware ergoCub Robot
</h1>


<div align="center">

_"Towards a Shared Embodied Intelligence of Humanoid Robots: Optimization, Development, and Testing of the Human-Aware ergoCub Robot"_

Carlotta Sartore, Mohamed Elobaid, Lorenzo Rapetti, Giulio Romuladi, Stefano Dafarra, Nicola A. Piga, Ines Sorrentino, Paolo Maria Viceconte, Silvio Traversaro, Ugo Pattacini, Luca Fiorio, Francesco Draicchio, Giovanna Tranfo, Lorenzo Natale, Marco Maggiali, Daniele Pucci

Submitted to *Nature Machine Intelligence* for consideration
</div>

This repository contains the code associated with a paper submitted to *Nature Machine Intelligence*.
The following libraries are required to run the code.

- [**adam**](https://github.com/ami-iit/adam) — kinematics/dynamics library
- [**shared-controllers**](https://github.com/ami-iit/shared-controllers) — shared autonomy framework

Both are direct outcomes of the research and include their own installation documentation and integration tests. This repository focuses narrowly on the data and scripts required to reproduce the specific results reported in the paper.

## Repository Organization 📁 

The repository is organized into three main directories, each corresponding to a distinct architecture instance of the ergoCub robot:

- **`optimal_hardware/`** - Contains scripts and outputs for the hardware optimization process.
- **`physical_intelligence/`** - Contains scripts for human-robot interaction experiments.
- **`data/`** - Contains experimental data collected during the experimental campaign as well as hardware optimization results.

## Reproduce the paper results 📋


### First Architecture Instance: Optimal Hardware 🤖

This section includes the scripts required to replicate the hardware optimization performed for the ergoCub robot. The main documentation can be found in [README](https://github.com/ami-iit/paper_sartore_2025_ergocub_nature_machine_intelligence/tree/main/OptimalHardware)

#### Dependencies
- The optimization process depends on [adam](https://github.com/ami-iit/adam), which implements the core functionalities.

#### Contents
- The **scripts** for hardware optimization.
- The **output models** of the hardware optimization process.
- The **Docker recipe** for replicating the paper results.

### Second Architecture Instance: Physical Intelligence 🚶 🤝

This section includes the scripts required to replicate the human-robot interaction experiments. The main documentation can be found in [README](https://github.com/ami-iit/paper_sartore_2025_ergocub_nature_machine_intelligence/tree/main/PhysicalIntelligence)

#### Dependencies
- The code relies on the [shared controllers](https://github.com/ami-iit/shared-controllers) library, which implements the main functionalities.

#### Contents
- The **scripts** for human-robot interaction experiments.


