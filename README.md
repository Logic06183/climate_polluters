

---

# Climate Pollutant Analysis

This repository contains a Jupyter notebook that performs an analysis of climate pollutants from various entities around the globe. The analysis aims to highlight the contributions of different entities to global emissions, with a specific focus on South African companies.

## Notebook Overview

`emissions_analysis.ipynb`:

- Loads emissions data from a provided CSV file (`emissions_high_granularity.csv`).
- Analyzes global pollutant data to identify the top emitters worldwide.
- Focuses on South African entities and their contribution to global emissions.
- Provides a detailed breakdown of emissions types for specific companies, such as Sasol.
- Visualizes emission trends over time.
- Critiques the impact of these companies on climate change.

## Data

The data used in this notebook includes the following fields:

- `year`: The year of the emissions data.
- `parent_entity`: The parent company or entity responsible for the emissions.
- `parent_type`: The type of entity (e.g., State-owned, Private).
- `commodity`: The commodity produced (e.g., Oil & NGL, Natural Gas).
- `production_value`: The production volume.
- `production_unit`: The unit of production volume (e.g., Million bbl/yr).
- `total_emissions_MtCO2e`: Total emissions in million tonnes of CO2 equivalent.

## Usage

To run the notebook:

1. Ensure you have Jupyter installed. If not, you can install it using Anaconda or pip.
2. Clone the repository.
3. Navigate to the cloned directory and launch Jupyter Notebook.
4. Open the `emissions_analysis.ipynb` notebook.
5. Run the cells sequentially to see the analysis and the results.

## Dependencies

- Python 3
- Pandas: For data manipulation and analysis.
- Matplotlib: For creating static, interactive, and animated visualizations in Python.
- Seaborn: For high-level interface for drawing attractive and informative statistical graphics.

## Contributing

Contributions to this analysis are welcome. Please fork the repository and submit a pull request with your proposed changes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---
