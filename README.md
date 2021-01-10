# Pentaho-Tableau-covid-19-visualisation

Retrieved three different COVID-19 datasets from Git Hub repositories to the local device.

Country Data - https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data
USA Data - https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data
Continent - https://github.com/owid/covid-19-data/tree/master/public/data


I have Split country wise covid cases into multiple folders(where each folder has csv files based on different file formats). Selected only required columns and replaced certain string values with appropriate values.

Using pentaho created 3 transformations and combined them under one job(datamart).

Three main tables created to store data from three different data files.

Customized tables were created using SQLyog from three main tables for tableau visualizations. 

Visualized the data based on country, continent, test cases, confirmed, death, recovered and population tables using Tableau.
