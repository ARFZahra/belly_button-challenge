# belly_button-challenge

Challenge Overview
This challenge aims to build an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels. The dashboard allows users to visualize the microbial diversity of an individual's belly button by displaying various charts and demographic information.

The repository contains the following files and folders:
•	index.html: The main HTML file that structures the dashboard.
•	samples.json: The dataset containing information about microbial samples and demographic data.
•	app.js in statics folder:  The JavaScript file that handles data processing, visualization, and interactions.

Setting Up the Repository:
Created a new repository called belly-button-challenge. Cloned the repository to the local machine. Added the StarterCode folder containing the challenge files, including index.html, samples.json, and the static/js  folder with working JavaScript- app.js

Reading the Data:
Used the D3 library to read in samples.json from the provided URL: https://static.bc-edx.com/data/dla-1-2/m14/lms/starter/samples.json.
Processed the data to extract relevant information for the dashboard.
Creating the Metadata Panel: Built a panel to display the sample's metadata, such as demographic information, by following the instructions in the starter code.
Used a loop to iterate through each key-value pair in the metadata JSON object and created a text string to display the information. Appended the text to the #sample-metadata panel using HTML tags.

Building the Horizontal Bar Chart:
Created a horizontal bar chart to display the top 10 OTUs (Operational Taxonomic Units) found in an individual.
Integrated a dropdown menu to allow users to select different samples.

Building the Bubble Chart:
Created a bubble chart with the following features:
x-axis: otu_ids
y-axis: sample_values
Marker sizes: Determined by sample_values
Marker colors: Based on otu_ids
Hover text: Displayed otu_labels

Updating the Dashboard:
Implemented functionality to update all the charts and metadata panel when a new sample is selected from the dropdown menu.

Deploying the Dashboard:
Deployed the dashboard as a static web app on GitHub Pages, making it publicly accessible. This step was particularly exciting as it allowed the dashboard to be easily shared and viewed by others.

Deployment
The dashboard is deployed on GitHub Pages and can be accessed through the following link: 
https://arfzahra.github.io/belly_button-challenge/

