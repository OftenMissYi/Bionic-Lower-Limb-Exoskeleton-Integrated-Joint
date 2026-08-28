# 🦿 Bionic Lower-Limb Exoskeleton Integrated Joint

Design and performance analysis of an integrated joint drive unit for a bionic lower-limb exoskeleton, developed as my undergraduate graduation project.

The project focused on the mechanical design and integration of a compact knee joint actuator, combining a high-power-density BLDC motor, planetary gearbox and torque sensing into an integrated drive unit. The designed actuator was also integrated into an existing lower-limb exoskeleton structure through an in-situ replacement approach.

## 🔧 Key Contributions

* Designed an integrated knee joint drive unit for a bionic lower-limb exoskeleton
* Developed a single-stage NGW planetary gearbox with a reduction ratio of 3.75
* Performed motor selection and transmission parameter design
* Designed the integrated mechanical structure, including the housing, shaft system, output interface and supporting components
* Integrated a torque sensor into the drive transmission chain
* Designed the drive unit for direct integration with an existing exoskeleton structure
* Performed structural and performance analysis using finite element and multibody dynamics simulation
* Evaluated stress, deformation, output speed, motor torque and transmission error under rated and peak load conditions
* Proposed a hierarchical control architecture combining gait-phase recognition, impedance control and ADRC-based trajectory tracking

## ⚙️ Design Overview

The actuator follows a quasi-direct-drive (QDD) concept based on a high-power-density BLDC motor and a compact planetary gearbox.

The main design targets included:

* Peak output torque: ≥ 55 N·m
* Rated output torque: 21 N·m
* Joint operating range: 0–160°
* Planetary gearbox ratio: 3.75
* Target transmission efficiency: ≥ 90%

The integrated design combines the drive, transmission and torque sensing functions into a compact coaxial mechanical system.

## 🧮 Simulation & Analysis

The designed drive unit was evaluated through both finite element analysis and multibody dynamics simulation.

### Finite Element Analysis

Structural simulations were used to evaluate the planetary gearbox and integrated mechanical structure under representative loading conditions, including stress, strain and deformation.

### ADAMS Multibody Dynamics

A multibody dynamics model was developed to evaluate the dynamic behaviour of the planetary transmission under changing load conditions.

The analysis included:

* Output angular velocity
* Motor driving torque
* Gear meshing forces
* Transmission error
* Dynamic response under rated and peak torque loading

The simulation results were used to verify the feasibility of the mechanical design and its ability to meet the target performance requirements.

## 🧠 Control Strategy

A hierarchical control concept was developed for the integrated joint drive system, consisting of gait-phase recognition, dual-mode control and low-level motor control.

The proposed strategy combines adaptive impedance control during the support phase with ADRC-based trajectory tracking during the swing phase.

The control architecture was developed at the theoretical/software level as part of the project. Physical prototype and hardware-in-the-loop validation were outside the completed project scope.

## 📁 Repository Structure

```text
Bionic-Lower-Limb-Exoskeleton/
├── CAD/
│   ├── Drive_Unit/
│   ├── Planetary_Gearbox/
│   └── Exoskeleton_Integration/
│
├── Simulation/
│   ├── ANSYS/
│   └── ADAMS/
│
└── docs/
    ├── project_report_excerpt.pdf
    └── defense_presentation.pdf
```

The repository contains the original CAD and simulation project files together with selected documentation from the undergraduate thesis and defense presentation.

Some CAD and simulation files retain their original Chinese filenames and may require the corresponding commercial software to open.

## 🛠️ Technologies

`SolidWorks` · `ANSYS Workbench` · `MSC Adams` · `Planetary Gearbox` · `Mechanical Design` · `Finite Element Analysis` · `Multibody Dynamics` · `Robot Actuation`

## ⚠️ Project Scope & Limitations

This project focused primarily on the mechanical design, integration and simulation-based evaluation of a single knee joint drive unit.

The project did not include:

* Physical prototype fabrication
* Experimental validation on a wearable exoskeleton
* Hardware-in-the-loop testing
* Multi-joint gait experiments

The repository therefore represents the engineering design and simulation stage of the project rather than a fully experimentally validated exoskeleton system.

## 📚 Documentation

Selected pages from the original undergraduate thesis are provided in `docs/` together with the complete defense presentation for additional technical background and design details.
