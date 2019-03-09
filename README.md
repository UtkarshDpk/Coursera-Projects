# Project_1
This is a project in Python which uses K-means clustering algorithm to cluster various neighbourhoods in Toronto. 
We start by first creating a dataframe by web-scraping wikipedia page for neighbourhoods and boroughs along with their postal codes.
Then based on the postal codes we add coordinates of every neighbourhood to the dataset and then start analyzing the dataset using Foursqaure api.
Using this API we explore each neighbourhood for top ten venues belonging to different categories. 
Finally we cluster the neighbourhoods and create a Folium map to depict the clusters.
