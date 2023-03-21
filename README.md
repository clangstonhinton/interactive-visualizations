# interactive-visualizations
"Belly Button Challenge"

Use JavaScript, HTML, css, D3 and Plotly to build an interactive dashboard application that explores the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.  The dataset can be found here: https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of the study participants, while the rest were relatively rare.

## Approach

- Used the D3 library to read in samples from the URL dataset
- Created a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in each study participant
- Created a bubble chart that displays all the OTU samples collected from the study participant
- Created a gauge chart that depicts the number of weekly belly button washings for each participant
- Displayed the metadata (demographic information) for each participant including: ID, ethnicity, age, gender, location and washing frequency
- All the charts and metadata changes when a new study participant is selected in the dropdown menu
 
## Example Website App

- To see the live version of the website application, download the source code and launch index.html. 


## Technology
- JavaScript
- D3
- HTML
- CSS
- Plotly
