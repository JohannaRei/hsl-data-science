# Will I be late today?
An analysis of various factors that contribute to the delay of Helsinki's public transport lines.

## Data
Live bus tracking data has been collected from the Helsinki Regional Transport Authority (HSL). Live data was collected every minute for two weeks and saved to a daily archive.

Weather data has been collected from the DarkSky API.

## Running
Tasks are held in various Jupyter notebooks
- Raw_HSL_Live_Data_Parser.ipynb - Parse the raw data that was scraped from the HSL API to a usable format
- Data_Cleanup.ipynb - Combine datasources, imputate, and clean the data
- Data_Science.ipynb - Various classifiers
- Visualisations.ipynb - Graphs of the results of data analysis
