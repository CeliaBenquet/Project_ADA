# How food shapes the World

# Abstract
With 7.7 billion people around the world in 2019, food demand outbreak has raised serious concerns regarding productive agricultural land availability. As for now cultivable surface expansion has been the only real solution, this project aims at providing insights on how this problematic is currently shaping the world’s surface as we know it. 
Investigation will first focus on the kind of environment that are being impinged on. Moving on to the “destructive” impact of certain foodstuffs and diet trends, correlating with international trade flows. 
This study relies on FAOSTAT data set from the United Nation, helping us in the process.  
We endeavor at providing an exhaustive visualization of the world under growing food reshaping pressure. Key features will be surface evolution across time and space, selected crops impact as well as involved parties and areas. Tackling all of the above with both social awareness and self consciousness concerns.

# Research questions
- What is the global evolution of the cultivated surface per country from 1995 to 2007?
- What is the area lost of savanna, shrubland, grassland and forest per country per year?
- Do we see a correlation between the area lost by ecosystems and the area gain by agriculture?
- For each selected crop, sojabean, banana, wheat, rice and palm oil, what pourcentage of the total cultivated area do they represent? 
- If there is a correlation between an increase in area cultivated and area lost from all the ecosystems, what would be approximatively the area lost because of the selected crops in particular?
- Are sojabean, banana, wheat, rice and palm oil meant for exportation and/or importation for each country over the years? Check more precisely for different economical segments and regions. 
- How can we identify  short term food trends and what is its impact on the global and country wise area loss?

# Dataset
We will use data sets taken from FAOSTAT published by the United Nation and related to food and agriculture. It gives us a really broad set of informations to answer to our problematic. We selected 4 data sets. 

First, we want an insight on where food is produced. “Fao_data_crops_data.csv” will give us the surface of new plantations for every kind of products through time in the different countries of the world by looking at “Area Harvested” for every product. We can also investigate data for a particular type of product. For example, we could find out about rentable products when comparing the “Area Harvested” to the “Production Quantity”. 

As we also would like to have an idea about what kind of ecosystem is lost to benefit to agriculture, we will investigate the files “Emissions_Agriculture_Burning_Savanna_E_All_Data_(Norm).csv” and “Emissions_Land_Use_Forest_Land_E_All_Data_(Norm)”. The first one lists diverse information on burnt savannas such as the quantity of burnt biomass or the different gas emissions. We can look at “Area Burnt” to analyze the surface of savanna replaced for agriculture. Similarly for the second one, the major part of the data set consists of informations about gas emissions. For our study, the interesting value is the superficie of burnt forests, “Area”, that, as for savannas, we can use to answer our initial question. 

Finally, as we also would like to develop on a more social aspect of the problem, we would like to investigate the quantities of imports and exports using the data set “Trade_Crops_Livestock_E_All_Data_(Normalized).csv”. This data set consists of a lot of different commercialized products, not all of them coming from agriculture so we would have to select maybe 5 to 10 food products we find interesting to study (maybe after investigating on the first data set). Using the informations “Export Quantity” and “Import Quantity”, we can find out which countries are the biggest “providers” and which ones are depending on others regarding the selected products. 
This data set is completed by another one coming from FAO listing commodities and corrresponding codes. This will allow us to choose our crop  depending on commodity group.
The data sets are CSV files, smaller than 0.1 GB, which is easily manageable. 


List of the used data sets: 
- Emissions_Agriculture_Burning_Savanna_E_All_Data_(Norm).csv (less savana )
- Fao_data_crops_data.csv \\where every products are planted
- Emissions_Land_Use_Forest_Land_E_All_Data_(Norm) (less forests )
- Trade_Crops_Livestock_E_All_Data_(Normalized).csv (imports and exports)
- export_items_1574515779.csv (Fao commodity) 


# A list of internal milestones up until project milestone 3
This will do those following steps until Milestone 3: 
* More precise analysis of the data for each questions
* Answer to the questions by getting the exact processing of the dataFrames 
* Understand how to have a world map representation on Folium
* Proper vizualisation of the results with Folium 
* Analysis and discussion of the results based on the vizualisation and final answers to question
* Do the data story 

# Questions for TAa
- How to map our values on a world map seperated by country boundaries. Is there a way to link the country names to an area on the map (Folium, implemented map)? 
- Is there any particular tool other than linear metrics for trend observation ? 

