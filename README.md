# Geothermal Energy Supply Curve Analysis (EGS 4k Limited Access, Moderate)

This project analyzes geothermal potential across the United States using data from the **Open Energy Data Initiative (OEDI)**. It applies spatial, statistical, and supply curve analysis to evaluate enhanced geothermal system (EGS) potential, infrastructure access, and state-level scalability.

## Objectives
- Evaluate geothermal site capacity and proximity to transmission infrastructure.
- Identify top states with strong EGS potential.
- Apply the DKIW (Data–Knowledge–Information–Wisdom) framework for insight development.

## Repository Structure

data/ – Raw and cleaned data files

scripts/ – Main analysis scripts (.Rmd and .R)

docs/ – Rendered report outputs (HTML, PDF, DOCX)

figures/ – Exported figures for quick preview

## Key Findings
- Western U.S. dominates geothermal distribution, especially California and Nevada.
- **Texas** and **New Mexico** show the highest development potential due to low transmission distances.
- **Montana** and **Utah** offer strong geothermal gradients but higher infrastructure costs.

## Technical Details
- Language: R  
- Packages: `dplyr`, `ggplot2`, `sf`, `scales`, `forcats`, `tinytex`  
- Report Format: `.Rmd` knitted to HTML/PDF  
- Data Source: [Open Energy Data Initiative (OEDI)](https://data.openei.org/submissions/8383)
  - Note: (Dataset is located in data/ if web link is inaccessible).
