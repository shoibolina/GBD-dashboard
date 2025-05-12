# GBD-dashboard using D3.js
An interactive D3.js dashboard to visualize country-level Disability-Adjusted Life Years (DALYs) from the Global Burden of Disease dataset (IHME GBD 2021). This project enables users to explore global health trends by disease and year via a choropleth map.  
![gbd-demo](https://github.com/user-attachments/assets/0b9decf2-9090-4d37-9405-80391ecf70b2)

## Technologies
- Frontend: HTML, CSS, JavaScript (D3.js v7)
- Visualization: D3 Geo (for maps), D3 Scale, D3 Axis
- Data Cleaning: Python, pandas

## Dataset
Source: [IHME Global Burden of Disease (GBD) 2021](https://vizhub.healthdata.org/gbd-results?params=gbd-api-2021-permalink/9b20a1709046c2a140a766ad0f14c9d1)

Filtered to include:
  - Metric: Number, Rate
  - Age: All ages
  - Sex: Both sexes
  - Cause: Select all 3 level cause

The downloaded dataset is preprocessed using Python (pandas) to standardize country names and export a cleaned CSV for D3 rendering
