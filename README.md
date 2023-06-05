# Module_14-BellyButton_Challenge
This repository contains the solution for the Belly Button Challenge project. The project focuses on creating interactive web visualizations using the D3 library. The goal is to display and analyze data related to belly button biodiversity.

## Requirements
* Python v3.10.9

## Instructions
To complete the Belly Button Challenge, follow these steps:

1) Use the D3 library to read the data from the provided URL: samples.json.
2) Create a horizontal bar chart with a dropdown menu to display the top 10 Operational Taxonomic Units (OTUs) found in each individual. The chart should have the following features:
* Use sample_values as the values for the bar chart.
* Use otu_ids as the labels for the bar chart.
* Use otu_labels as the hovertext for the chart.

3) Create a bubble chart that displays each sample. The bubble chart should have the following features:
* Use otu_ids for the x values.
* Use sample_values for the y values.
* Use sample_values for the marker size.
* Use otu_ids for the marker colors.
* Use otu_labels for the text values.

4) Display the sample metadata, which includes an individual's demographic information. 
5) Ensure that all the plots update dynamically when a new sample is selected from the dropdown menu. Feel free to create a custom layout for your dashboard.
6) Adapt the Gauge Chart from [Plotly Gauge Charts](https://plot.ly/javascript/gauge-charts/) to plot the weekly washing frequency of the individual.
   - You will need to modify the example gauge code to account for values ranging from 0 through 9.
   - Update the chart whenever a new sample is selected.


## References
Hulcr, J. et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/Links to an external site.
