# Introduction

In Ontario, all elementary aged students are assessed on their academic performance through a provincial assessment in grades 3 and 6.  Private organizations, like the Fraser Institute, use the public data generated from these assessment to rank schools across the province.  The outcome of this misguided ranking, is the negative characterization of school neighbourhoods based on an assessment tied to academic achievement of developing children.  Fraser Institute uses EQAO data and some socioeconomic data to complete this analysis.

Although schools are the hub of communities for young families, neighbourhoods are much more than the academic achievement scores of still developing children.  

This report will analyze school neighbourhoods from the Kitchener/Waterloo area in relation to local amenities (venues) and cluster local schools of similar community characteristics together.  These clusters will be compared to the Fraser Institute rankings for further analysis.

This information can help families new to the region consider a school community's merits in a more holistic manner, and also help school communities connect with the neighbourhood partners (i.e. identify community agencies and groups that might connect with the school team).

# Data Sources

Location data from geopy / Nominatim - to connect the Fraser Institute school data with the location data from FourSquare.

Foursquare location data (www.foursquare.come) - the location data will be used to create a better picture of school communities (venues, amenities) to better inform families and school staff.

Fraser Institute School Ranking data (https://www.fraserinstitute.org/school-performance) - these school ratings will be used to select schools for the analysis.  Rating data will be compared to the clustering results of the Foursquare community data for further discussion.  This may contain some school sites that will not be included in this report, as the schools are too small to represent a fuller community cluster.
  
# Methodology
section which represents the main component of the report where you discuss and describe any exploratory data analysis that you did, any inferential statistical testing that you performed, if any, and what machine learnings were used and why.

The school ranking data from the Fraser Institute was scraped and cleaned of null values and irrelevant schools (i.e. small independent schools).
School geographic locations were assigned through geopy and a plot was created demponstrating that the schools represent an acceptable coverage of the Kitchener-Waterloo region.
<figure class="image"><img src="schools.png" alt="Map of schools."><figcaption>The distribution of schools in the K-W area.</figcaption></figure><\center>

The Fraser Institute data consists of school Ratings for the 2017-18 school year as well as provincial Rankings out of 3044 schools in the Province of Ontario.  The data was used to create an initial clustering of schools based on these two dimentions.  Euclidian distance was used for the K Means Clustering algorithim.  This algorithm was selected as it will handle of complexity of clustering school neighbourhoods with the large number of factors that will be included with FourSquare data during this analysis.  The 'elbow method' was used to select the best k-clusters value.
# Results 
section where you discuss the results.
    
# Discussion 
section where you discuss any observations you noted and any recommendations you can make based on the results.
    
# Conclusion 
section where you conclude the report.



