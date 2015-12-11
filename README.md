# Statistical_Programming_project
Analysis of Genus Specimen and their occurrences

Summary :
This Project analyzes the reported illnesses caused by genus species data,time, location and provides an insights and determines the top genus species that are causing illnesses in US as well as provides a brief report of the Top 3 states effected with the viruses along with the names of genus species. 
One more report regarding the Top species effecting US and their affecting regions .These reports will give an idea about the type of precautions that are to be taken inorder to reduce the illnesses as well as to reduce them in particular State.


Data Source :http://wwwn.cdc.gov/foodborneoutbreaks/ --> Download Data --> Excel Download current search data (Excel).


Data Structure:
1.Year(1998 - 2014)
2.Month
3.State
4.Genus Species
5.Illnesses
6.Hospitalization
7.Death
8.Etiology Status

Link :http://wwwn.cdc.gov/foodborneoutbreaks/

Parameters Considered for analysis :
1.Year
2.Month
3.State
4.Genus Species
5.Illnesses

Project Description :
1.Projecting data of Genus Species affected States
2.Seasonal Analysis

Packages Used : 
1.pandas - Dataframes.
2.matplotlib.pyplot - Plotting the Data.
3.numpy - Mathematical Operations.
4.matplotlib.colors -->rgb2hex-To covert the hexadecimalvalue(value,value,value) to color(R,G,B).
5.matplotlib.patches -->Polygon - Creates a shape from the values of basemap and can also be used to add color to polygon.
6.matplotlib.patches--> Patch () - Saves all the polygons and project it on the map.
7.Collections --> Counter - To determine the counts and store the maximum recurring item.
8.mpl_toolkits.basemap --> basemap - Used to convert the shapefile to basemap which can be used


Terms:

#llcrnrlon	longitude of lower left hand corner of the desired map domain (degrees).
#llcrnrlat	latitude of lower left hand corner of the desired map domain (degrees).
#urcrnrlon	longitude of upper right hand corner of the desired map domain (degrees).
#urcrnrlat	latitude of upper right hand corner of the desired map domain (degrees).




