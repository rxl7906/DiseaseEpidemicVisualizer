# Choropleth Map Visualization of the Zika Disease Epidemic within the US

![Alt text](https://www.dropbox.com/s/zjejfocdqak76oo/4_20_2016.png?dl=0 "Optional title")
# Problem #
Whenever there is a disease epidemic, specialists such as the CDC would like to track the origins of the disease and understand how it migrated over time. How can we provide a visual aspect to understanding how a disease migrates among the human population over time?

# Dataset #
The dataset is from Kaggle: https://www.kaggle.com/cdc/zika-virus-epidemic
The dataset consists of the Zika virus migration across the world. I took the data concerned with Zika disease occurrences within the United States.

# Implementation #
1) Pre-processed the US Zika Disease occurrences to identify and provide state abbreviations so that the Plotly API understands where to plot a data point
2) For every date, an image is produced showing all the Zika occurrences within the US.

# Technologies/APIs used #
- Python (Juypter notebook) - curate the data for each report date, feed the curated data for a Plotly API call to generate the Choropleth map. 
- Plotly API - generate the Choropleth map

# Future #
- Fix image generation
- Provide UI for looping thru timeline of images

# Issues faced #
- There exists geographic mapping libraries however due to the many different varibles you can have, there are a lot of geographic mapping libraries to search thru in order to find the one that suits your dataset.
