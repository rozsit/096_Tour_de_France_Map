# 096_Tour_de_France_Map  
# Tour de France Start and Finish Towns Heatmap

This project visualizes the distribution of start and finish towns in the history of the Tour de France (1903–present) as a density heatmap.  
It uses Python, GeoPandas, Matplotlib, and Seaborn for data processing and advanced map plotting.

---

## Features

- Cleans and preprocesses Tour de France stage data (start/finish towns, coordinates, weights).
- Plots towns as proportional markers, with top cities labeled.
- Visualizes density using a weighted KDE heatmap.
- Highlights France and neighboring countries on a custom map.
- Adds professional cartographic elements: north arrow, scale bar, city legend, data source/copyright.
- Axis ticks and gridlines shown as latitude and longitude.
- Publication-quality output, with easy export to PNG.

---

## Installation

1. **Install Python dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

---

## Usage

1. **Prepare your data:**
    - Place `TDF_Stages_with_coords.csv` in the `data/` folder.
    - Download and unzip the Natural Earth countries shapefile (`ne_10m_admin_0_countries.shp` and associated files) into a `geo/` folder.

2. **Run the code:**
    - Open and execute the Jupyter Notebook (`.ipynb`) or run the Python script in the `src/` directory to generate the map.
    - The resulting map is saved as a high-resolution PNG.

---

## Directory Structure

├── data/  
│ └── TDF_Stages_with_coords.csv  
├── geo/  
│ └── ne_10m_admin_0_countries.shp  
├── requirements.txt  
└── README.md
