# Dataset Characteristics

**[Notebook](exploratory_data_analysis.ipynb)**

## Dataset Information

### Dataset Source
- **Dataset Link:** It is a private data set, but we can provide it (Dataset is in the located in this folder)
- **Dataset Owner/Contact: Christoph Emeis

### Dataset Characteristics
- **Number of Observations:** Number of samples: 874, we have daily data from 23.06.2023 to 13.11.2025
- **Number of Features:** 9

### Target Variable/Label
- **Label Name:** Solar Power generation (kWh)
- **Label Type:** Regression
- **Label Description:** 
 Our label is the solar power generation of a solar plant.We want to predict the solar power generation of a privatly owned solar plant, by using a weather forecast
- **Label Values:** The daily solar power generation ranges from 0 to 50 kWh
- **Label Distribution:** 
 The solar power generation is higher in the summer and lower in winter, so it varies periodically. 

### Feature Description

- air temperature (Tavg): average local air temperature two meter above ground (°C)!
- max temperature (Tmin): maximum local air temperature two meter above ground (°C)!
- min temperature (Tmax): minumum local air temperature two meter above ground (°C)!
- humidity (Hum): Relative Humidity (%)!
- Vapor pressure deficit (VPD): Evaporation Proxy (kPa)
- Precipitation height (Prec): amount of rain/snow that would accumultate on a flat surface (mm)!
- Precipitation binary (Pbin): Did it rain or not (0/1)
- Wind speed (Wspd): Average wind Speed (m/s)
- Gust (Wmax): Wind Gust Max (m/s)
- Wind direction (Wdir): Wind Direction Vector Mean (deg)  
- Cloud coverage (Cld): Percentage of cloud coverage (Oktas)!
- Solar radiation (Sol): solar radiation (J/cm2)      
- Sunshine duration (Sun): how long did the sun shine (h) !
- Pressure (Pres): air pressure (hPa)!
- visibility (Vis): how far you can see (m)!
- soil temperature (Soil): average local soil temperature 5cm (°C)
- time!

********Right now, we only described the data for one of our two locations, we have data from a solar plant in Elmshorn, we are also thinking about including a second location (Dobersdorf), in that case we will expand our dataset if everything goes well, we will also try to use data from the whole of germany**********

## Exploratory Data Analysis

The exploratory data analysis is conducted in the [exploratory_data_analysis.ipynb](exploratory_data_analysis.ipynb) notebook, which includes:

- Data loading and initial inspection
- Statistical summaries and distributions
- Missing value analysis
- Feature correlation analysis
- Data visualization and insights
- Data quality assessment
