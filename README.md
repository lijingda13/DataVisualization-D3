# Global Renewable Energy Data Visualization
This visualization provides an integrated view of global energy data, emphasizing renewable energy production, access to electricity, and the relationship between population, GDP, and renewable capacity.

<img width="1512" alt="2024-11-08 17 43 18" src="https://github.com/user-attachments/assets/73bb053a-fc46-4f22-9c51-b5fa82082c89">

## Features
- Interactive Charts: D3.js-powered graphs that reflect energy generation trends, GDP, and CO2 emissions.
- Mapbox Integration: A global map indicating population percentage with access to electricity.
- Data Filtering: Ability to select different countries and years to filter the data shown in the charts and map.

## Running the Visualization
To run the visualization locally on your machine, please follow these steps:

### Online Access (St. Andrews University)
You can access the visualization online through the University of St. Andrews' network at the following URL:

```url
https://jl404.teaching.cs.st-andrews.ac.uk/D3/sustainable_energy.html
```

### Preparation:

- Ensure you have a modern web browser installed (e.g., Chrome, Firefox, Safari).
- Download the entire folder containing the HTML, CSS, and CSV data files provided with the visualization.

### Data Files:

- The CSV data file must be named global-data-on-sustainable-energy.csv and located in the directory `data`.
- The CSV should contain columns for Year, Entity, Population, Access to electricity, Renewable-electricity-generating-capacity, GDP, and CO2 emissions data, along with geographic coordinates for the mapping (Latitude and Longitude).

### Libraries and APIs:

- This visualization uses D3.js v7 and Mapbox GL JS v2.7.0.
Ensure you have internet access to load the D3.js library and Mapbox API.

### Access Token:

- Replace 'Your_Mapbox_Access_Token_Here' with your actual Mapbox access token in the HTML file.

### Run the Visualization:

- Open the HTML file in your browser by double-clicking it or right-clicking and selecting your preferred browser.
- If required, set up a local server if your browser restricts loading local files due to CORS policy.

### Interact with the Visualization:

- Use the "Select Country" dropdown to view data for different countries.
- Adjust the "Year" slider to update the visualization for different years.
- Hover over elements in the charts to view detailed data tooltips.
