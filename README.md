![Sample Graph](Resources/logo.png)

# Sales Forecast - Animated Graphs

## Description 

A dashboard which includes sales forecast data, and an analysis of historical sales.. 



## Table of Contents
* [Run](#Results)
* [Tools](#Tools)
* [Data](#Data)
* [Graphs](#Graphs)
* [Contributors](#Contributors)
* [Contact](#Contact)



## Run

This app is hosted on Heroku:

[Sales Forecast App](https://instantoffice.herokuapp.com/)


  
## Graphs

Daily cases and deaths for entire pandemic. User can zoom in as well as see daily tallies by moving their cursor over the graph.  

![Sample Graph](static/graph_sample.png)

Shows the risk level, trend, and ICU capacity for the area presently. (I calculate trend by taking the total confirmed cases of the last seven days and comparing it the previous week.)

![Sample Graphs](static/graphs_3.png)



## Tools

JavaScript, Plotly.js, D3, Bootstrap, HTML5, CSS, Flask, Python



## Data

This app pulls data the following data from the [COVID ACT NOW API](https://apidocs.covidactnow.org/).

<b>New Cases:</b>  New confirmed or suspected cases.<br>
<b>New Deaths:</b>  New deaths since previous report with erratic values removed by outlier detection.<br>
<b>Total Cases:</b>  Cumulative confirmed or suspected cases.<br>
<b>Total Deaths:</b>  Cumulative deaths that are suspected or confirmed to have been caused by COVID-19.<br>
<b>Fully Vaccinated:</b>  Total number of people completing vaccination - currently those completing their second shot.<br>
<b>Partially Vaccinated:</b>  Ratio of population that has initiated vaccination.<br>
<b>Risk Level:</b>  The overall risk level is based on caseDensity, testPositivityRatio, and infectionRate.<br>
<b>New Cases Trend:</b>  The increase or decrease of newly confirmed cases for state or county as compared to the previous week.<br>
<b>Icu Bed Capacity:</b>  Information about ICU bed utilization details.<br>



## Contact

Feel free to contact me with examples or any questions via the information below:

GitHub: [@julia-claira](https://api.github.com/users/julia-claira)

Email: julia-claira@gmail.com
