# Limonium Hydroponics Analysis

This repository contains a private and ongoing analysis workflow for a hydroponic Limonium experiment. The project combines nutrient solution monitoring, plant measurements, and image-based phenotyping using Jupyter Notebook, Python, PlantCV, and R.

## Experiment Overview
The experiment is conducted in a hydroponic house with four treatment sections:

- T1: Osmocote 500 mg N/L
- T2: Osmocote 1000 mg N/L
- T3: Osmocote 1500 mg N/L
- T4: Peters Excel hard water

## Data Collected
### Nutrient solution data
- pH
- EC
- Nutrient solution temperature
- Dissolved oxygen
- Nitrite

### Plant measurements
- Leaf number
- Vigor score
- Flower measurements at later stage

### Image-based traits
- Leaf area
- Plant diameter
- Color index

## Workflow
1. Collect hydroponic nutrient and plant observation data
2. Capture top-view plant images
3. Process images in Jupyter Notebook using PlantCV/OpenCV workflow
4. Extract phenotyping traits
5. Analyze treatment differences in R/Python

## Repository Structure
- `notebooks/` Jupyter notebooks for image analysis and exploratory work
- `scripts/` R and Python scripts
- `data_sample/` sample cleaned datasets
- `images/` example raw images
- `results/` example outputs and plots
- `docs/` notes and supporting documentation

## Current Status
Ongoing experiment. This repository contains selected sample files and representative outputs only.

