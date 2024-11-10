# EDA of Adult Asthma-COPD Audit Data
This project provides an exploratory data analysis (EDA) of data from the National Asthma and COPD Audit Programme. Using Python, statistics are analysed related to asthma and Chronic Obstructive Pulmonary Disease (COPD) across 159 hospitals, covering admissions, bed space, staff availability, and more.

## Project Structure
- **copd-asthma-analysis.ipynb**: Jupyter Notebook containing all code and analysis.
- **asthmadata.csv**: Data file containing respiratory illness statistics across hospitals.
- **map_data.geojson**: GeoJSON file for visualizing geographical data using Folium.
- **requirements.txt**: List of required packages for replicating the environment.

## Features
The notebook provides:
- Data wrangling functions for handling multi-index headers and organizing hospital data categories.
- Interactive data exploration using ipywidgets to filter and view categories, column selections, and row control.
- Visualizations using matplotlib, plotly, and folium for interactive geographic leaflet mapping and data plots.

## Setup Instructions
1. Clone the repository:
    - `git clone https://github.com/mtk3276/copd-asthma-data-analysis.git`
    - `cd copd-asthma-data-analysis`
2. Install dependencies:
    - Use the requirements.txt file to install all necessary packages:
        `pip install -r requirements.txt`
    - Alternatively, install packages directly:
        `pip install numpy pandas matplotlib ipywidgets plotly folium seaborn scikit-learn statsmodels`

## Running the notebook
*Please visit [Installing Jupyter](https://jupyter.org/install) for guidance on installing Jupyter Lab and Jupyter Notebook.*

1. Open the notebook:
    - `jupyter notebook copd-asthma-analysis.ipynb`
2. Run the notebook cells (run all) to explore data, generate visualisations and interact with datasets. Scroll to **Mapping Data** to view leaflet map visualisations. 

## Data Description
- **asthmadata.csv** - data contains statistics on respiratory illnesses for hospitals around the UK, inluding hospital regions, hospital admissions, service provided and number of beds available. 
- **NHS_England_Regions_Map.geojson** - contains region boundary data for plotting leaflet chloropeth maps.

## Dependencies
This project uses the following Python packages:
- numpy, pandas - for data manipulation
- matplotlib, seaborn, plotly - for data visualisation
- ipywidgets - for interactive controls
- folium - for geographical visualisation

## Acknowledgments
Data from the [National Asthma and COPD Audit Programme](https://www.data.gov.uk/).
