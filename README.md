# Bile Predicaments

Analysis and prediction of bile duct conditions, specifically focusing on intraductal concrement (bile duct stones).

## Overview

This repository contains statistical analysis and machine learning approaches for predicting bile duct conditions. The project includes:

- **Statistical Analysis (R)**: Descriptive statistics, diagnostic test performance metrics, and visualizations
- **Machine Learning (Python)**: Prediction models using TensorFlow Decision Forests

## Project Structure

```
├── analysis.Rmd          # R Markdown analysis with statistical methods
├── bile.ipynb            # Python notebook for ML-based prediction
├── bile_nostone.ipynb    # Additional analysis notebook
├── idc.ipynb             # Intraductal concrement analysis
├── data/                 # Data directory (Excel files)
└── bile.Rproj            # RStudio project file
```

## Requirements

### R Dependencies
- tidyverse
- openxlsx / readxl
- compareGroups
- gtsummary
- caret
- ggpubr / ggsci
- FactoMineR / factoextra
- ROCit

### Python Dependencies
- pandas
- numpy
- scikit-learn
- tensorflow
- tensorflow-decision-forests
- dtreeviz
- matplotlib

## Usage

### R Analysis
Open `analysis.Rmd` in RStudio and knit to generate the HTML/PDF report with descriptive statistics and diagnostic test evaluations.

### Python Notebooks
Run the Jupyter notebooks (`bile.ipynb`, `idc.ipynb`) for machine learning-based prediction models.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Hans Christian Stubbe (2025)
