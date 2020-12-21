# Segmenting-and-Clustering-Toronto-Neighborhoods
This repository scrapes a webpage with all the zip codes +neighborhoods of Toronto, Canada. It gets the venues in those locations from foursquare.com. lastly, it segments Toronto area into 5 clusters and checks the most frequent venues in those clusters. 

# Detailed-description
This repository contains 3 files. the result of part 1 and 2 are stored in .csv files to be used for the next part. 

1. Part 1: This part scrapes a wikipedia page with all the neighborhood and zip codes of Toronto, Canada. The webpage has other information, too. The job is to read the required information and write them to a dataframe. Sone primary data processing is also done here.

2. Part 2: This part gets the latitudes and longitudes of each neighborhood based on their zip code. Geocoder package is used.

3. Part 3: This part gets the top venues in Toronto area from foursquare.com. The imported .json file is read and required information is stored into a dataframe. It also segments the area with k-means clustering. Scikit-learn is used for clustering. Matplotlib and Folium packages are used for mapping.
