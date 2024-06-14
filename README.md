# Assignment 4 Data Preprocessing and feature engineering

This project focuses on analyzing an energy dataset to understand the relationships between different variables, select important features, and visualize the results using heatmaps. Additionally, it examines the impact of missing values on the dependent variable.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to preprocess an energy dataset, handle missing values, and select important features using a RandomForestRegressor. The selected features are then visualized using a heatmap to understand their correlations. The project also explores the relationship between missing values and the dependent variable, `Energy_Production_MWh`.

## Dataset

The dataset contains various columns related to renewable energy sources, financial details, and energy production. Ensure your dataset is named `energy_dataset_.csv` and includes the following columns:

- `Type_of_Renewable_Energy`
- `Funding_Sources`
- `Installed_Capacity_MW`
- `Energy_Production_MWh`
- `Energy_Consumption_MWh`
- `Energy_Storage_Capacity_MWh`
- `Storage_Efficiency_Percentage`
- `Initial_Investment_USD`
- `Financial_Incentives_USD`
- `GHG_Emission_Reduction_tCO2e`
- `Air_Pollution_Reduction_Index`
- `Jobs_Created`
- `Energy_Production_Per_Capacity`
- `Energy_Consumption_Per_Capacity`
- `Net_Energy_Production`
- `Storage_Efficiency`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Celebal_Assign4.git
   cd Assignment4
   ```
2. Install the required Python packages:
   ```bash
   Copy code
   pip install -r requirements.txt
   ```
## Usage

Ensure your dataset file energy_dataset_.csv is in the repository directory.

Run the analysis script:

```bash
Copy code
python analysis.py
The script will preprocess the dataset, handle missing values, select important features, and generate visualizations, including a heatmap showing correlations between selected features.
```

## Features
```bash
Data Preprocessing: Handles missing values, scales numerical features, and creates interaction terms.
Feature Selection: Uses RandomForestRegressor to select important features.
Visualization: Generates heatmaps to visualize feature correlations and boxplots to examine the impact of missing values on the dependent variable.
Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
```
## License
This project is licensed under the MIT License - see the LICENSE file for details.
