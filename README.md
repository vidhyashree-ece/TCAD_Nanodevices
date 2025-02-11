**TCAD Simulation Files for Nanoelectronics Devices**
This repository contains simulation source code files for various nanoelectronic devices, designed for execution in DeckBuild software. The simulations explore the characteristics and performance of different transistor technologies.

**Experiments Included**
The repository includes .in files for the following seven experiments:

1. FET (Field-Effect Transistor)
2. SET (Single-Electron Transistor)
3. TFET (Tunnel Field-Effect Transistor)
4. GFET (Graphene Field-Effect Transistor)
5. Nanowire Transistor
6. Nanotube Transistor
7. Tunnel Devices

After execution, the simulations generate results in the following formats:

.str files – Structure files containing device geometry and material properties (viewable in TCAD).
.log files – Log files with simulation results, including electrical characteristics and performance metrics.

**Software Requirements**
DeckBuild (for running .in input scripts)
Tonyplot and Tonyplot 3D (for analyzing .str and .log files)

**Usage Instructions**
Open the desired .in file in DeckBuild.
Run the simulation to generate .str and .log output files.
View and analyze the output using Tonyplot 3D.

**License**
This repository is intended for research and educational purposes. Feel free to modify and expand the simulations for further experimentation.
