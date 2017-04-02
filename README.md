# Choropleth Map Visualization of the Zika Disease Epidemic within the US

![Alt Text](https://github.com/rxl7906/DiseaseEpidemicVisualizer/raw/master/ChoroplethMaps/4_20_2016.png)

Link below provides slideshow:
http://htmlpreview.github.io/?https://github.com/rxl7906/DiseaseEpidemicVisualizer/blob/master/slideshow.html

# Problem #
Whenever there is a disease epidemic, CDC specialists track the origins of the disease and try to understand how it migrated over time. How can we provide a visual aspect to understanding how a disease migrates among the human population over time?

# Proposed Solution #
The goal would be to provide a disease tracker to record real-time occurrences and updates. If we could visualize where there's a influx of occurrences we could potentially contain the disease and prevent it from spreading.

# Dataset #
The dataset is from Kaggle: https://www.kaggle.com/cdc/zika-virus-epidemic
The dataset consists of the Zika virus migration across the world. I took the data concerned with Zika disease occurrences within the United States.

# Implementation #
1) Pre-processed the US Zika Disease occurrences to identify and provide state abbreviations so that the Plotly API understands where to plot a data point
2) For every date, an image is produced showing all the Zika occurrences within the US.

# Technologies/APIs used #
- Python (Juypter notebook) - curate the data for each report date, feed the curated data for a Plotly API call to generate the Choropleth map. 
- Plotly API - generate the Choropleth map
- Javascript/HTML/CSS - used for rendering the slideshow

# Future #
- Fix image generation

# Issues faced #
- There exists geographic mapping libraries however due to the many different varibles you can have, there are a lot of geographic mapping libraries to search thru in order to find the one that suits your dataset.


# Other applications #
Human Trafficking - Track when and where human trafficking activity happens and send law enforcers to arrest criminals.
Crime - Track when and where crime happens across the world and send law enforcers to those areas. 
Finance - Where and when did somebody make a transaction? Fraud detection
