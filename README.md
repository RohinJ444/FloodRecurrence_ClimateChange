# Analyzing the Recurrence of Significant Flood Events in New Jersey and the Impact of Climate Change on Flood Recurrence

## Overview
I conducted this analysis as my final project for EPS 88 at UC Berkeley. I analyzed 75 years of hydrological data from three stream/river stations in New Jersey to contextualize the magnitude of recent flooding events and evaluate the impact of climate change on flood recurrence.

## Project Contents
1. **Notebook**: A Jupyter notebook (`FloodDataAnalysis.ipynb`) containing additional context and background research, the data analysis, and the respective visualizations.
2. **Datasets**: Three datasets with mean daily stream/river discharge data from 1947 to 2022.

## Description
Floods are the deadliest meteorological phenomena in the United States, with extreme flooding events recorded with increased frequency. This project examines the annual maximum flood events in New Jersey and calculates their exceedance probabilities and recurrence intervals. The analysis uses three representative hydrological stations in northern, central, and southern New Jersey, representing various water body types (stream, creek, and river).

## Methodology
- **Data Collection**: Mean daily discharge data for three hydrologic stations in New Jersey from 1947 to 2022.
- **Data Preparation**: Filtering mean daily discharge data to create a new dataframe with annual maximum discharge for each year.
- **Frequency Analysis**: Fitting the data to a log-normal distribution to estimate the probability of each maximum annual discharge and its recurrence interval.

## Key Concepts
- **Exceedance Probability**: The probability that a given flood magnitude will be exceeded in any given year.
- **Recurrence Interval**: The inverse of the exceedance probability, representing the average time between exceedances of a given flood magnitude.

## Results
The results include the exceedance probabilities and recurrence intervals for the maximum annual mean daily discharge at each of the three hydrologic stations. The analysis uses the binomial probability formula to determine the likelihood of the sequence of extreme flooding events recorded at these stations.

## License
This project is licensed under the MIT License.
