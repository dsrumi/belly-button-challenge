# belly-button-challenge
Module 14 Challenge

In this assignment, we built an interactive dashboard to explore the Belly Button Biodiversity datasetLinks to an external site., which catalogs the microbes that colonize human navels.

The dataset revealed that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.


We created a new repository for this project called belly-button-challenge and used the D3 library to read in samples.json from the URL https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json.

Then we created a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual and used sample_values as the values for the bar chart,otu_ids as the labels for the bar chart and otu_labels as the hovertext for the chart.

![image](https://static.bc-edx.com/data/dl-1-2/m14/lms/img/hw01.jpg)

Then we created a bubble chart that displays each sample and used otu_ids for the x values,sample_values for the y values,sample_values for the marker size,otu_ids for the marker colors and otu_labels for the text values.

![image](https://static.bc-edx.com/data/dl-1-2/m14/lms/img/bubble_chart.jpg)

 Finally, we displayed the sample's metadata, i.e., an individual's demographic information by looping through each key-value pair from the metadata JSON object and creating a text string and appending an html tag with that text to the #sample-metadata panel.

![image](https://static.bc-edx.com/data/dl-1-2/m14/lms/img/hw03.jpg)

