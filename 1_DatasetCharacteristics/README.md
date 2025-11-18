# Dataset Characteristics

**[Notebook](exploratory_data_analysis.ipynb)**

## Dataset Information

### Dataset Source
- **Dataset Link:** [Provide a direct link to your dataset. If the dataset is private, explain the reason and provide contact information for the dataset owner]
- **Dataset Owner/Contact:** [If applicable, provide contact information for private datasets]

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

- air temperature ():average local air temperature two meter above ground
- humidity (): 
- soil temperature (): average local soil temperature
- precipitation height(): amount of rain/snow that would accumultate on a flat surface
- air pressure(): air pressure (mbar)
- visibility(): how far you can see (km)
- solar radiation(): sum of solar radiation over the day
- sunshine duration(): how long did the sun shine
- cloud coverage (): percentage of cloud coverage averaged over the day




********Right now, we only describbed the data for one of our two locations, we have data from a solar plant in Elmshorn, we are also thinking about including a second location (Dobersdorf), in that case we will expand our dataset if everything goes well, we will also try to use data from the whole of germany**********

## Exploratory Data Analysis

The exploratory data analysis is conducted in the [exploratory_data_analysis.ipynb](exploratory_data_analysis.ipynb) notebook, which includes:

- Data loading and initial inspection
- Statistical summaries and distributions
- Missing value analysis
- Feature correlation analysis
- Data visualization and insights
- Data quality assessment
