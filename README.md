# Geospatial Analysis of Health Facilities in Nigeria

Welcome to the Geospatial Analysis of Health Facilities in Nigeria repository! This project performs an in-depth geospatial analysis to explore and evaluate health facilities across Nigeria's geopolitical zones. The analysis includes data extraction, transformation, loading (ETL), and visualization, providing valuable insights into health facility distribution and quality.

## Project Overview

This repository contains:

- **Data Extraction & Transformation:** Processing and cleaning various datasets related to health facilities in Nigeria.
- **Geospatial Analysis:** Analysis of health facilities based on their locations, scores, and administrative boundaries.
- **Visualization:** Charts and maps to visualize top-rated health facilities and their distribution.
- **SQLite Database:** Final datasets stored in an SQLite database for easy access and analysis.

## Datasets

The following datasets were used in this analysis:

- **Local Government Area (LGA) Admin Boundary (Shapefile):** Geographic boundaries of local government areas.
- **Health Facility Locations (CSV):** Geographic locations of health facilities across Nigeria.
- **Health Facilities Scoring (MapInfo file):** Scoring and evaluation of health facilities.
- **LGA Senatorial Districts (Excel):** Administrative divisions within the LGAs.

## Getting Started

To run this analysis on your local machine, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/geospatial-health-facilities-nigeria.git
   ```
   
2. **Install Dependencies:**
   Ensure you have Python installed and then install the necessary packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Analysis:**
   Execute the Jupyter Notebook to perform the ETL processes and analysis:
   ```bash
   jupyter notebook
   ```

4. **Explore Results:**
   Open the notebook to view detailed analysis, visualizations, and insights into health facilities.

## Contributing

Contributions are welcome! If you have suggestions for improvements or additional features, please open an issue or submit a pull request.
