# Weld-Deformation-software-development-and-validation

## Overview

Weld deformation is an emerging and complex area in finite element analysis (FEA), and at the time of my onboarding, Bobcat had not yet established an internal process for conducting reliable weld deformation simulations. The task was treated as an R&D initiative, with the goal of demonstrating the value of simulation-based weld distortion prediction to the broader engineering team.

## Challenges Addressed

- No in-house knowledge of how to set up and run weld deformation simulations.
- No standardized workflow or tooling pipeline from CAD to results.
- Limited understanding of required simulation parameters such as clamping, fixturing, heat input, and weld sequencing.
- No prior validation data or modeling benchmarks.

## My Contributions

- **Toolchain Development**: Established a full simulation pipeline from PLM (Windchill) through Creo Parametric CAD modeling and geometry cleanup, mesh preparation using ANSYS tools, and manual quad meshing in ESI SysWeld.
- **Parameter Calibration**: Conducted extensive experiments on small welded samples with varying parameters and sequences to understand real-world inputs.
- **Data Collection**: Visited factory floors to gather weld sequences, clamping positions, fixturing setups, and operational heat input settings.
- **Project Simulations**: Applied the workflow to real production projects including excavator clamps, articulated loader frames, mower decks, and mower casters. Simulations accurately predicted deformation trends and provided corrective recommendations.
- **Documentation & Training**: Built internal guides and documentation covering each step of the workflow. Trained a new hire remotely on simulation setup and use.
- **Knowledge Sharing**: Delivered a company-wide technical presentation introducing the capabilities of weld deformation simulation. Demonstrated its potential to reduce post-weld rework, accelerate production ramp-up, and cut prototyping costs.

## Technologies Used

- **CAD**: Creo Parametric (via Windchill PLM)
- **Pre-processing**: ANSYS tools for geometry cleanup and model simplification
- **Meshing & Simulation**: ESI SysWeld (manual mesh, solid quad elements)
- **Validation**: On-site measurements and physical test samples

## Outcomes

- Enabled Bobcat’s first successful in-house weld deformation simulations.
- Identified and mitigated major distortion contributors before production.
- Saved costs associated with rework and scrap through pre-production validation.
- Laid the groundwork for a company-wide adoption of simulation-based weld planning.

> **Note**: Result images and raw simulation files are proprietary and cannot be publicly shared.

## Repository Structure

This repository includes general documentation and sanitized sample models to demonstrate the process framework (without proprietary data).

## Author

**Tejas Chhajer**  
Advanced Manufacturing Intern @ Doosan Bobcat  
[LinkedIn](https://www.linkedin.com/in/tchhajer/)
"""

from pathlib import Path

# Save the readme to a file
readme_path = Path("/mnt/data/README_Weld_Deformation_Simulation.md")
readme_path.write_text(readme_text)

readme_path.name

Analyzed
python
Always show details

Copy
from pathlib import Path

readme_text = """
# Weld Deformation Simulation

This project documents my work on developing and validating a weld deformation simulation capability during my internship with Doosan Bobcat (May 2023 – May 2024). The simulation workflow, built using ANSYS and ESI SysWeld, aimed to predict thermal distortion in welded structures, support mitigation strategies, and provide pre-production confidence for large fabricated assemblies.

## Overview

Weld deformation is an emerging and complex area in finite element analysis (FEA), and at the time of my onboarding, Bobcat had not yet established an internal process for conducting reliable weld deformation simulations. The task was treated as an R&D initiative, with the goal of demonstrating the value of simulation-based weld distortion prediction to the broader engineering team.

## Challenges Addressed

- No in-house knowledge of how to set up and run weld deformation simulations.
- No standardized workflow or tooling pipeline from CAD to results.
- Limited understanding of required simulation parameters such as clamping, fixturing, heat input, and weld sequencing.
- No prior validation data or modeling benchmarks.

## My Contributions

- **Toolchain Development**: Established a full simulation pipeline from PLM (Windchill) through Creo Parametric CAD modeling and geometry cleanup, mesh preparation using ANSYS tools, and manual quad meshing in ESI SysWeld.
- **Parameter Calibration**: Conducted extensive experiments on small welded samples with varying parameters and sequences to understand real-world inputs.
- **Data Collection**: Visited factory floors to gather weld sequences, clamping positions, fixturing setups, and operational heat input settings.
- **Project Simulations**: Applied the workflow to real production projects including excavator clamps, articulated loader frames, mower decks, and mower casters. Simulations accurately predicted deformation trends and provided corrective recommendations.
- **Documentation & Training**: Built internal guides and documentation covering each step of the workflow. Trained a new hire remotely on simulation setup and use.
- **Knowledge Sharing**: Delivered a company-wide technical presentation introducing the capabilities of weld deformation simulation. Demonstrated its potential to reduce post-weld rework, accelerate production ramp-up, and cut prototyping costs.

## Technologies Used

- **CAD**: Creo Parametric (via Windchill PLM)
- **Pre-processing**: ANSYS tools for geometry cleanup and model simplification
- **Meshing & Simulation**: ESI SysWeld (manual mesh, solid quad elements)
- **Validation**: On-site measurements and physical test samples

## Outcomes

- Enabled Bobcat’s first successful in-house weld deformation simulations.
- Identified and mitigated major distortion contributors before production.
- Saved costs associated with rework and scrap through pre-production validation.
- Laid the groundwork for a company-wide adoption of simulation-based weld planning.

> **Note**: Result images and raw simulation files are proprietary and cannot be publicly shared.
