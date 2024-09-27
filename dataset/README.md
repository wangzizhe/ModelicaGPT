# Dataset

The current focus is on power and energy systems. Therefore, only a representative libraries in these fields have been selected.

Ongoing work: Introducing debugging prompt pairs into the dataset.

## Summary

* Total prompt pairs: 10104
* File size: 26.05 MB

## Information

### Modelica libraries:

* [A collection of free and commercial libraries](https://modelica.org/libraries)

### General Cleanup Strategies (applied to all libraries):

* The following components have been excluded:

  * Resources (visualization)

  * Icons (visualization)

  * UsersGuide (text descriptions for human)

  * ModelicaTest

* Annotations:
  * If documentation is found inside annotations, use the documentation as the description
  * If annotations only contains visualizations, delete the annotations

## List of Considered & Converted Libraries

|                         Name & Repo                          | Version & Release Date |                         Description                          | Considered for Dataset? |
| :----------------------------------------------------------: | :--------------------: | :----------------------------------------------------------: | :---------------------: |
| [Standard Library](https://github.com/modelica/ModelicaStandardLibrary) |  v4.1.0 (2024-02-06)   |                  Modelica Standard library                   |           Yes           |
| [VehicleInterfaces](https://github.com/modelica/VehicleInterfaces) |  v2.0.0 (2024-08-19)   | Interface definitions and architectures for vehicle system modeling |           Yes           |
|    [AixLib](https://github.com/modelica-3rdparty/AixLib)     |  v2.0.0 (2024-08-19)   |               Building performance simulations               |           Yes           |
| [Buildings](https://github.com/modelica-3rdparty/Buildings)  |  v11.0.0 (2024-04-09)  |               Building performance simulations               |           Yes           |
| [ObjectStab](https://github.com/modelica-3rdparty/ObjectStab) |  v2.0.0 (2024-02-01)   | Power System Stability Studies (descriptions missing for each component) |           No            |
| [PhotoVoltaics](https://github.com/modelica-3rdparty/PhotoVoltaics) |  v2.0.0 (2021-07-19)   |        Simulation of photo voltaic cells and modules         |           Yes           |
|     [PNlib](https://github.com/modelica-3rdparty/PNlib)      |  v3.0.0 (2024-02-13)   |                        Modeling xHPN                         |           Yes           |
| [PowerGrids](https://github.com/modelica-3rdparty/PowerGrids) |  v1.0.4 (2023-12-10)   |        Electro-mechanical modelling of power systems         |           Yes           |
| [PowerSystems](https://github.com/modelica-3rdparty/PowerSystems) |  v2.0.0 (2024-05-07)   | Modeling electrical power systems both in transient and steady-state mode |           Yes           |

### 1. Converted Modelica Standard Library

Extracted components: 2085

* 457 packages
* 1434 models
* 194 blocks

Prompt-completion pairs: 2082 (size: 7.28 MB)

Clean up strategies:

* General strategy


### 2. Converted Vehicle Interfaces Library

Extracted components: 169

* 53 packages
* 115 models
* 1 block

Prompt-completion pairs: 169 (size: 171 KB)

Clean up strategies:

* General strategy
* Exclude package "ObsoleteVehicleInterfaces2" as library version description
* Exclude Package "VehicleInterfacesTestConversion2" as conversion test for issue #38
* Exclude package "UsersGuide"

### 3. Converted AixLib Library

Extracted components: 2736

* 1515 packages
* 1087 models
* 134 blocks

Prompt-completion pairs: 2597 (size: 5.9 MB)

Clean up strategies:

* General strategy
* Exclude package "Obsolete" 

### 4. Converted Buildings Library

Extracted components: 4752

* 2274 packages
* 1873 models
* 605 blocks

Prompt-completion pairs: 4750 (size: 11.3 MB)

Clean up strategies:

* General strategy
* Exclude package "Obsolete" 

### 5. Converted PhotoVoltaics Library

Extracted components: 62

* 16 packages
* 43 models
* 3 blocks

Prompt-completion pairs: 62 (size: 87.3 KB)

* All components have descriptions

Clean up strategies:

* General strategy

### 6. PNlib

Extracted components: 179

* 22 packages
* 143 models
* 14 blocks

Prompt-completion pairs: 170 (size: 313 KB)

Clean up strategies:

* General strategy

### 7. PowerGrids

Extracted components: 187

* 38 packages
* 143 models
* 6 blocks

Prompt-completion pairs: 178 (size: 284 KB)

Clean up strategies:

* General strategy

### 8. PowerSystems

Extracted components: 97

* 97 packages

Prompt-completion pairs: 96 (size: 702 KB)

Clean up strategies:

* General strategy
