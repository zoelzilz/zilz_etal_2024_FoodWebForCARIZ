This README.txt file was generated on 2024-06-16 by Z. Zilz 

**GENERAL INFORMATION**

1\. Title of the Project: A parasite-inclusive food web for the California rocky intertidal zone  

2\. This repository includes all of the data files and R script necessary to construct and visualize a food web representing all known and logically inferred trophic interactions in the California rocky intertidal zone. 
 
3\. Author Information 
 
A. Corresponding Author Contact Information 
Name: Zoe L. Zilz 
Institution: University of California Santa Barbara, Department of Ecology, Evolution, and Marine Biology 
Email: zoelzilz@gmail.com 
 
B. Co-author(s) Contact Information 
Name: Emily Hascall
Institution: Sonoma State University 
Email: hascalle@sonoma.edu 
 
Name: Athena DiBartolo 
Institution: University of California Santa Barbara, Bren School of Environmental Science 
Email: athenamdibartolo@gmail.com 
  
Name: Delen Flores 
Institution: University of California Santa Barbara, Department of Ecology, Evolution, and Marine Biology 
Email: delen.flores6@gmail.com 
 
Name: Sophie Cameron 
Institution: University of California Santa Barbara, Department of Ecology, Evolution, and Marine Biology 
Email: smcameron.photography@gmail.com 
 
Name: Jaden E. Orli 
Institution: University of California Santa Barbara, Department of Ecology, Evolution, and Marine Biology 
Email: jadenorli@gmail.com 
 
C. Alternate Contact Information 
Name: Armand Kuris 
Institution: University of California Santa Barbara, Department of Ecology, Evolution, and Marine Biology 
Email: kuris@lifesci.ucsb.edu 
 
4\. Date of data collection or obtaining: 
All data obtained/collected between 2019-09-01 and 2024-06-15. 
 
4\. Geographic location of data collection: California, USA 
 
5\. Data collection was funded by the University of California Santa Barbara Coastal Fund, Grant #CF-202110-00396 
 
**SHARING/ACCESS INFORMATION** 
 
1\. Licenses/restrictions placed on the data: none 
 
2\. Links to publications that cite or use the data: [doi will go here when paper is accepted for publication] 
 
3\. Links to other publicly accessible locations of the data: https://github.com/zoelzilz/zilz_etal_2024_FoodWebForCARIZ 
 
5\. See references.csv for full list of original data sources. 
 
6\. Recommended citation for the project: 
Zilz, et al. (2024). A parasite-inclusive food web for the California rocky intertidal zone. [Dataset]. 
 
 
**DATA & FILE OVERVIEW**
 
1\. File List: 
 
Note: all files in the data repository must be present in your working directory in order for the food web visualization and summary code to run.
 
DATA FILES 
*nodes.csv* - a node list with metadata representing all known California rocky intertidal taxa and their life stages, where appropriate 
*links.csv* - a link list with metadata representing all trophic interactions known or inferred between nodes in the California rocky intertidal, including parasitism 
*references.csv* - a list of references used for assembling, justifying, and generating confidence rankings for nodes and links within the web 
*column_descriptors.csv* - a file containing column header and metadata code definitions 
 
R MARKDOWN FILES 
*cariz_foodweb_visualization.rmd* - Code for the visualization of the California rocky intertidal food web as a network graph and as a matrix. 
*cariz_foodweb_metrics.rmd* - Code to generate commonly used metrics for a large network, including connectance, link density, mean degree, etc. 
 
**METHODOLOGICAL INFORMATION**
 
1\. For full methodology please see the associated data descriptor publication.
 
2\. Data were cleaned and visualized using R version 4.4.0 -- "Puppy Cup"
 
