# Victorian Housing Data Integration and Reshaping

## Overview
This project integrates multiple datasets into a single schema for housing information in Victoria, Australia, and reshapes the data to prepare for linear regression modeling. The project involves data integration, reshaping, and documentation.

## Key Features

### Data Integration
- Integrates several datasets into a unified CSV file.
- Combines XML, JSON, shapefiles, and web-scraped data into a consistent schema.
- Ensures proper data formatting, including handling missing values and Haversine distance calculations.

### Data Reshaping
- Examines different normalization and transformation methods to standardize the data.
- Analyzes the impact of various transformations on the data, focusing on linearity and scale.
- Prepares the data for linear regression modeling, without building the actual model.

### Setup and Prerequisites
- **Python 3.x**: Ensure you have Python installed on your system.
- **Jupyter Notebook**: To run the provided notebook.
- **Required Libraries**: Install the following packages:
  ```sh
  pip install pandas numpy scipy lxml bs4
  ```
### Running the Project
- Open the Jupyter notebook (31940757_ass3.ipynb) in Jupyter Notebook or Google Colab.
- Run the code to integrate the datasets and reshape the data.
- Verify that the output CSV file (31940757_A3_solution.csv) has the correct structure and data.  

### Input Files
- **XML Data:** Contains property information in XML format.
- **JSON Data:** Additional property information in JSON format.
- **Shapefiles:** Geographic data for Victorian suburbs and LGAs.
- **PDF Data:** Mapping between LGAs and suburbs.
- **Web-Scraped Data:** Housing-related information from a specific website.

### Output Files
- Integrated Data: A CSV file (31940757_A3_solution.csv) with the integrated housing information.

### Methodology
The project follows a systematic approach to data integration and reshaping:
- Data Integration: Combines multiple data sources into a single schema, ensuring correct structure and handling default values.
- Data Reshaping: Applies normalization and transformation methods to prepare data for linear regression modeling.
- Documentation: The Jupyter notebook includes detailed explanations of the steps, along with proper code comments and structure.

### Authors
- [Pragy Parashar](https://github.com/pragy29)

