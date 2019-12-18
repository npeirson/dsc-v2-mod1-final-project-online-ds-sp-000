# Predicting Housing Sale Prices in King County, WA  
Contained herein is an exploration of housing sale prices in King County, as well as an attempt to model them. This method yeilds an r squared of 90%.


## Description of files  
- **kc_house_data.csv** - The primary dataset containing details and sale prices for houses sold in the King County area between 05/02/14--05/27/15.  
- **student.ipynb** - Notebook containing EDA and modeling.  
- **School_Sites_in_King_County__schsite_point.csv** - Spreadsheet containing information regarding each school in King County.  From [here.](https://gis-kingcounty.opendata.arcgis.com/datasets/school-sites-in-king-county-schsite-point)
- **distances_to_schools_by_type.csv** - Spreadsheet of distances to schools by types of school for each house in the `kc_house_data.csv` dataset.  
- **nearest_schools_by_type.csv** - Spreadsheet containing nearest school name for each type of school in the `School_Sites_in_King_County__schsite_point.csv` dataset for each house in the `kc_housing_data.csv` dataset.  
- **Neighborhood_Centers_in_King_County__neighborhood_centers_point.csv** - Spreadsheet containing information regarding central business districts in King County. From [here.](https://gis-kingcounty.opendata.arcgis.com/datasets/neighborhood-centers-in-king-county-neighborhood-centers-point)
- **hoods_data.csv** - Spreadsheet containing nearest neighborhood and the distance therefrom for each house in the `kc_house_data.csv` dataset.
- **stepwise_result.npy** - A numpy array of the names of columns that survived the culling of stepwise feature selection (i.e. p < 0.05). 
- **presentation.pdf** - A presentation on the findings of this project.
- **map.png** - Image backdrop for map visualizations.
