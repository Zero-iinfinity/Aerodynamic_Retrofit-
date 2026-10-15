# Aerodynamic_Retrofit
# ADDITIVE AERO — 3D-Printed Vortex Generator Retrofit for Wind Turbines

ADDITIVE AERO explores the aerodynamic performance improvement of small-scale vertical-axis wind turbines (VAWTs) using 3D-printed vortex generators (VGs). The project investigates how modifying airflow around a blade can influence aerodynamic characteristics and rotor performance.

The approach combines airfoil-based design, CAD modelling, additive manufacturing, and comparative performance analysis to develop a modular retrofit concept for small-scale wind energy applications.

## Project Objectives

- Design a vortex generator compatible with a vertical-axis wind turbine blade.
- Investigate the aerodynamic effects of vortex generators on blade performance.
- Compare baseline and modified configurations using relevant aerodynamic metrics.
- Explore additive manufacturing as a method for rapid prototyping and design optimization.
- Assess the potential of retrofit-based solutions for decentralized renewable energy applications.

## Project Overview

| Component | Description |
|---|---|
| Project Name | ADDITIVE AERO |
| Application | Small-scale wind energy |
| Turbine Type | Vertical-axis wind turbine (VAWT) |
| Airfoil | NACA 0018 |
| Primary Technology | Additive manufacturing |
| Design Method | CAD modelling and aerodynamic analysis |
| Main Component | Vortex generator |
| Key Metrics | Power coefficient, rotor power, and aerodynamic performance |
| Application Context | Renewable energy and sustainability |

## Working Principle

Vortex generators are small aerodynamic elements designed to generate streamwise vortices in the flow around a surface. These vortices can help transport higher-momentum fluid toward the near-wall region and may delay flow separation under suitable operating conditions.

In this project, a vortex generator is incorporated into the blade configuration to investigate its influence on the aerodynamic performance of a vertical-axis wind turbine.

The workflow is:

1. Select the baseline airfoil geometry.
2. Develop the vortex generator design using CAD.
3. Manufacture the component using 3D printing.
4. Integrate the vortex generator into the blade configuration.
5. Evaluate the baseline and modified configurations.
6. Compare the resulting aerodynamic and rotor-performance metrics.
7. Identify opportunities for further design optimization.

The effectiveness of the vortex generator depends on its geometry, position, orientation, operating conditions, and interaction with the blade's unsteady flow.

## Methodology

### 1. Airfoil Selection

The NACA 0018 airfoil is used as the reference blade profile for the aerodynamic study.

### 2. CAD Modelling

The blade and vortex generator geometries are developed using computer-aided design tools. The geometry is intended to support prototyping and comparative analysis.

### 3. Additive Manufacturing

The vortex generator can be fabricated using 3D printing, allowing rapid iteration of geometry and dimensions.

### 4. Aerodynamic Analysis

The baseline and modified configurations are evaluated using the methods implemented in the project. Depending on the available analysis, these may include computational simulation or experimental testing.

### 5. Performance Comparison

The configurations are compared using relevant metrics, including:

- Maximum power coefficient (\(C_{p,\max}\))
- Rotor power
- Tip-speed ratio (TSR), where available
- Aerodynamic characteristics, where evaluated

### 6. Design Optimization

The results can be used to investigate the influence of vortex generator geometry and placement on turbine performance.

## Reported Results

The following values represent the reported results for the configurations studied.

| Performance Metric | Baseline | With Vortex Generator |
|---|---:|---:|
| Maximum Power Coefficient (\(C_{p,\max}\)) | 0.1004 | 0.1202 |
| Reported Rotor Power | 1.195 W | 1.431 W |

### Relative Improvement in Maximum Power Coefficient

The relative improvement is calculated as:

\[
\frac{0.1202-0.1004}{0.1004}\times100
=19.72\%
\]

### Relative Improvement in Reported Rotor Power

\[
\frac{1.431-1.195}{1.195}\times100
\approx19.75\%
\]

These results indicate an improvement in the reported performance metrics for the studied configuration. The results should be interpreted in the context of the specific modelling or experimental conditions used. Further validation is required before generalizing the findings to other turbines or real-world operating conditions.

## Applications and Potential Impact

ADDITIVE AERO explores a retrofit-based approach to aerodynamic improvement rather than requiring complete turbine redesign.

Potential areas of application include:

- Small-scale renewable energy systems
- Distributed wind-energy research
- Aerodynamic prototyping and optimization
- Low-volume manufacturing of customized components
- Research into renewable-energy solutions for remote and rural locations

The project is aligned with the following United Nations Sustainable Development Goals:

- **SDG 7:** Affordable and Clean Energy
- **SDG 9:** Industry, Innovation and Infrastructure
- **SDG 12:** Responsible Consumption and Production

Application in Mizoram and other hilly regions would require local wind-resource assessment, site suitability analysis, and field validation.

## Repository Structure

The repository may be organized as follows:

```text
ADDITIVE-AERO/
├── CAD/
│   ├── blade_geometry/
│   └── vortex_generator/
├── Simulation/
│   ├── baseline/
│   └── vortex_generator/
├── Results/
│   ├── performance_comparison/
│   └── plots/
├── Documentation/
│   ├── methodology.md
│   └── references.md
├── Images/
├── README.md
└── LICENSE
```

The directory structure can be adapted to match the actual files included in the repository.

## Tools and Technologies

- CAD modelling software: [Insert software used]
- Aerodynamic analysis: [Insert simulation or experimental tools used]
- Additive manufacturing: 3D printing
- Airfoil geometry: NACA 0018
- Data analysis and visualization: [Insert tools used]
- Version control: Git and GitHub

Only tools actually used in the project should be listed.

## Limitations and Future Work

The current results apply to the configuration and conditions evaluated in the study. Additional work is needed to establish robustness and practical applicability.

Potential future work includes:

- Investigating different vortex generator geometries.
- Optimizing the position, height, spacing, and orientation of the vortex generators.
- Evaluating performance across a wider range of wind speeds and tip-speed ratios.
- Studying structural integrity, attachment strength, and fatigue resistance.
- Conducting controlled experimental validation.
- Assessing long-term durability under outdoor conditions.
- Performing a cost-benefit analysis using measured energy production and manufacturing costs.

## Getting Started

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY
```

Open the CAD files using the relevant CAD software. For simulation-based work, use the corresponding solver and configuration files included in the repository.

If the repository contains scripts or notebooks, follow the installation and execution instructions documented in their respective directories.

## Project Documentation

- **CAD Files:** [Insert link]
- **Simulation Files:** [Insert link]
- **Performance Results:** [Insert link]
- **Project Report:** [Insert link]
- **Demonstration Video:** [Insert link]

## Contributors

- [Your Name] — [Project role]
- [Contributor Name] — [Project role]
- [Contributor Name] — [Project role]

**Institution:** National Institute of Technology Mizoram

**Department:** Mechanical Engineering

## License

This project is released under the [MIT License](LICENSE), provided that the repository includes an MIT license file. Otherwise, replace this section with the license actually selected for the project.

## Acknowledgements

This project reflects the application of mechanical design, aerodynamic analysis, and additive manufacturing to a renewable-energy engineering problem.

## Disclaimer

This project is intended for research and educational purposes. Reported improvements are specific to the configurations and conditions evaluated. The design should not be considered commercially validated or suitable for unrestricted deployment without further aerodynamic, structural, safety, and field testing.
