# Density of Juvenile Salmon in Caithness Rivers

## Background
### How was the data gathered?
Information on the density of juvenile salmon was collected by a method called electrofishing. Various sites across six Caithness rivers were monitored over a range of years. The practicalities of these measurements involve either a bank-based generator and control box or equipment in a portable backpack format. The volume of the area of river tested must be estimated to allow the calculation of both mass and numerical densities. 

### Why was the data gathered?
The National Electrofishing Programme for Scotland (NEPS) is organised, run and reported on by Marine Scotland Science (MSS) and operates across Scotland; its purpose is to provide regional assessment of the status of juvenile salmon throughout Scotland. The Caithness District Salmon Fisheries Board (CDSFB) is responsible for collecting the data for NEPs from the Caithness rivers and they also sample sites which are outwith the NEPs programme. CDSFB are concerned with surveillance of the juvenile salmon stocks in each of the six Caithness rivers to enable advice to be provided to fisheries managers. 

## Motivation for Creating R-shiny Dashboard
Initially a Tableau dashboard was created with this data. After learning R Shiny I wanted to practice creating dashboards and felt that this dataset was ideal as it contained data which could be visualised both graphically and geospatially. 

## Usage
The shiny app can be accessed from the following link:  
https://e4z4az-fiona-carson.shinyapps.io/fish_dashboard/


![image](https://user-images.githubusercontent.com/105853308/213927538-4066e494-e93c-452a-987e-88e7b3a91bc2.png)


## Acknowledgements
I would like to thank Alan Youngson for valuable discussions which aided my understanding of the data and enabled the creation of this dashboard. I would also like to thank Marine Scotland who allow this data to be used under an Open Government Licence. 

## References
Reports on the data used to create this dashboard can be found at the following link:     
https://caithness.dsfb.org.uk/publications/

## Versions

R version 4.2.2 (2022-10-31)  
RStudio   2022.12.0+353  
plotly    4.10.1   
bslib     0.4.1     
readxl    1.4.0    
tidyverse 1.3.1  
leaflet   2.1.1   
shiny     1.7.2  
 
