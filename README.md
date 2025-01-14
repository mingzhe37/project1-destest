# IBPSA Project 1 - District Energy Simulation Test Procedure (DESTEST)

This repository contains the DESTEST (District Energy Simulation Test Procedure) developed within the IBPSA Project 1.

To establish reliable, decarbonized and sustainable cities, it is necessary to integrate all energy grids together with the different energy suppliers and end-users during the design, optimization and operation phases. To that matter, accurate urban-scale numerical models have to be developed to dynamically simulate buildings, infrastructures, networks, energy and matter fluxes. The multi-physics modelling language Modelica is particularly well-suited for that purpose.

The goal of the IBPSA Project 1 is to develop a BIM/GIS and Modelica framework for building and community energy simulation. Within the IBPSA Project 1, the DESTEST (Work Package 3.1) aims at testing district energy system simulations tools, and in particular, validate the urban energy systems models of the dedicated Modelica libraries. These currently dedicated Modelica libraries are as follows:
* _AixLib_, from RWTH Aachen University, Germany: https://github.com/RWTH-EBC/AixLib
 * _Buildings_, from LBNL, Berkeley, CA, USA: http://simulationresearch.lbl.gov/modelica
 * _BuildingSystems_, from UdK Berlin, Germany: http://www.modelica-buildingsystems.de
 * _IDEAS_ from KU Leuven, Belgium: https://github.com/open-ideas/IDEAS
All these libraries above are based on the core library _Modelica IBPSA library_: https://github.com/ibpsa/modelica-ibpsa

The DESTEST procedure consists in the comparison, benchmarking and thorough verification of a number of common exercises. In each common exercise, different participants are modelling and simulating a given case of buildings and/or energy grid with well-defined properties, characteristics, grid topology, weather conditions, and boundary conditions. The participants can use any suitable commercial or non-commercial simulation tools or the dedicated Modelica libraries. The simulation results of all participants are compared with each other by a dedicated Python-based time series comparison tool. Each common exercise is focusing on a particular aspect of the model output.

In order to stay within the scope of the IBPSA Project 1, the DESTEST common exercises are restricted to the simulation of buildings and cluster of buildings connected to district heating or district cooling networks only. However, the DESTEST procedure can be extended to other types of grid and network. The size of the simulated clusters ranges from a single building to several hundreds of buildings.

The primary goal of the DESTEST is to validate and benchmark urban-scale energy modelling tools. However, they are also used as a forum to discuss common mistakes and pitfalls that are encountered when modelling such systems. Guidelines for good modelling practices are established from the analysis and feedbacks of the common exercises. The DESTEST can also be used as training exercises for expert modellers, engineers, industry practitioners and students willing to build strong expertise in the dynamic simulation of urban-scale energy systems.

This online repository contains the detailed descriptions and the result data files of the different DESTEST common exercises. One can also find the Python-based time series comparison tool for benchmarking and analysis of the different common exercise results. This “DESTEST comparison tool” is available as both open-source Python file or executable file.
