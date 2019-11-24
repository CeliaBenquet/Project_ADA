# How food shapes the World

# Abstract
With 7.7 billion people around the world in 2019, food demand outbreak has raised serious concerns regarding productive agricultural land availability. As for now cultivable surface expansion has been the only real solution, this project aims at providing insights on how this problematic is currently shaping the world’s surface as we know it. 
Investigation will first focus on the kind of environment that are being impinged on. Moving on to the   “destructive” impact of certain foodstuffs and diet trends, correlating with international trade flows. 
This study relies on FAOSTAT data set from the United Nation, helping us in the process.  
We endeavor at providing an exhaustive visualization of the world under growing food reshaping pressure. Key features will be surface evolution across time and space, selected crops impact as well as involved parties and areas. Tackling all of the above with both social awareness and self consciousness concerns.

# Research questions
- What is the global evolution of the cultivated surface on a world scale from 1990 to 2014?
- What is the area lost of savanna, shrubland, grassland and forest per country?
- Do we see a correlation between the area lost by ecosystems and the area gain by agriculture?
- For each selected crop, Sojabean, banana, wheat, rice, palm oil, what pourcentage of the total cultivated area do they represent? 
- If there is a correlation between an increase in area cultivated and area lost from all the ecosystems, what would be approximatively the area lost because of these crops in particular?
- Check if sojabean, banana, wheat, rice, palm oil is meant for exportation and/or importation for each country over the years?

# Dataset
We will use data sets taken from FAOSTAT published by the United Nation and related to food and agriculture. It gives us a really broad set of informations to answer to our problematic. We selected 4 data sets. 

First, we want an insight on where food is produced. “Fao_data_crops_data.csv” will give us the surface of new plantations for every kind of products through time in the different countries of the world by looking at “Area Harvested” for every product. We can also investigate data for a particular type of product. For example, we could find out about rentable products when comparing the “Area Harvested” to the “Production Quantity”. 

As we also would like to have an idea about what kind of ecosystem is lost to benefit to agriculture, we will investigate the files “Emissions_Agriculture_Burning_Savanna_E_All_Data_(Norm).csv” and “Emissions_Land_Use_Forest_Land_E_All_Data_(Norm)”. The first one lists diverse information on burnt savannas such as the quantity of burnt biomass or the different gas emissions. We can look at “Area Burnt” to analyze the surface of savanna replaced for agriculture. Similarly for the second one, the major part of the data set consists of informations about gas emissions. For our study, the interesting value is the superficie of burnt forests, “Area”, that, as for savannas, we can use to answer our initial question. 

Finally, as we also would like to develop on a more social aspect of the problem, we would like to investigate the quantities of imports and exports using the data set “Trade_Crops_Livestock_E_All_Data_(Normalized).csv”. This data set consists of a lot of different commercialized products, not all of them coming from agriculture so we would have to select maybe 5 to 10 food products we find interesting to study (maybe after investigating on the first data set). Using the informations “Export Quantity” and “Import Quantity”, we can find out which countries are the biggest “providers” and which ones are depending on others regarding the selected products. 
The data sets are CSV files, smaller than 0.1 GB, which is easily manageable. 


List of the used data sets: 
- Emissions_Agriculture_Burning_Savanna_E_All_Data_(Norm).csv \\less savana 
- Fao_data_crops_data.csv \\where every products are planted
- Emissions_Land_Use_Forest_Land_E_All_Data_(Norm) \\less forests 
- Trade_Crops_Livestock_E_All_Data_(Normalized).csv \\imports and exports 


# A list of internal milestones up until project milestone 3
First of all, we will try to organize our work in the following way :
- Open the datasets, understand them deeply, clean them and filter out uninteresting columns/fields
- Split the work evenly between each team members to get the project going in an efficient manner
- Meet at least once a week to talk about how the project is going and see what has been done and what is left to do

Then we will set some weakly goals that we will strive to achieve and talk about during our meetings :
- Analyze the datasets, combine them and get the relevant informations that we need to answer our research questions (1st-2nd weeks)
- Develop and use graphical and interactive visualizations which will help us summarize and show our results (3rd week)
- Draw conclusions from our results and start thinking about the report (data story) (last week)

# Questions for TAa
- How to map our values on a world map seperated by country boundaries. Is there a way to link the country names to an area on the map (Folium, implemented map)? 

