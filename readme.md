# COVID-19 Cases, Deaths and vaccination Data Analysis and EDA

This repository contains Python code for retrieving and cleaning COVID-19 data from various sources. The data is analyzed to provide insights on the global spread of the virus, including the number of cases and deaths in different countries.

## Data Sources
The data used in this analysis is obtained from the following sources:

- John Hopkins University's Center for Systems Science and Engineering (JHU CSSE): This data includes the number of confirmed cases and deaths by location and date. The data is updated daily and can be found [here](https://github.com/CSSEGISandData/COVID-19).

- Our World in Data: This data includes information on COVID-19 vaccination rates by country. The data is updated daily and can be found [here](https://github.com/owid/covid-19-data/tree/master/public/data/vaccinations).

## Data Retrieval and Cleaning
The Python code in this repository retrieves the raw data from the above sources and cleans it for analysis. The cleaning process includes:

- Reshaping the data from wide to long format
- Converting date columns to proper datetime format
- Renaming columns for consistency
- Dropping unnecessary columns
- Calculating daily cases and deaths
- Filling missing data and filling NaN values
- Arranging columns in proper order
- Sorting data by country and date

## Data Analysis
The cleaned data is analyzed to provide insights on the global spread of COVID-19, including:

- Total cases and deaths by country
- Daily cases and deaths by country
- Vaccination rates by country
- Trends in cases and deaths over time

The analysis includes visualizations such as line plots and choropleth maps to help illustrate the data.

## Usage
To use this code, simply clone this repository and run the Python code in the Jupyter Notebook file. The notebook includes detailed explanations of each step of the analysis.

## Contributing
Contributions are welcome! If you find any errors or have suggestions for improving the analysis, please open an issue or submit a pull request.
