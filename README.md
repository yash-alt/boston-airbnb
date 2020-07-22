# boston-airbnb
This repo is about the analysis of Boston Airbnb dataset. We can find the prices and the location that are important factor for deciding the best fit for users.

 
### Introduction <a name="dataset-introduction"></a>
Data for analyzing trends in Boston's Airbnb is available for free on Kaggle.com.

### Project Motivation <a name="project-motivation"></a>
I chose this project to understand the trends of Airbnb in Boston area and analysis is done through addressing the following questions.
1. How well would we be able to foresee a posting’s cost and what highlights associate well with the estimating?
2. Where to put resources into a property in Boston to get the most extreme number of profits from Airbnb?
3. How well would we be able to foresee audits and what angles relate with reviews?

### Data features <a name="data-features"></a>
This dataset has 3,585 observations and 95 features. The features are price, review_scores_rating.

1. I had to clean up the values in several columns: the price column had a dollar sign ($) and comma (,) characters and was in object format. I removed these so the data can be translated into an integer.
2. The data types for other columns like the number of bedrooms, bathrooms, accommodates also required a change so they can be used in calculations.
3. Few columns such as neighbourhood_group_cleansed, jurisdiction_names, license, has_availability were dropped from the dataset as there were no recordings associated with them. These were all empty columns present in the data.
4. City column had a lot of duplicate entries with few case-sensitive entries, space addition issues, etc. All replicates were replaced with a single city code name and this cleaned data was put into a new column called city_cleansed in listings data. City column also had an unusual entry in some native language which was considered for dropping because there was only one entry as such and I was not losing so much data dropping it.

### File Descriptions <a name="files"></a>
The files used for this project are listed below and the repo has them too. 
1. reviews.csv - it has data related to listing's reviews.
2. calendar.csv - it contains listing's calendar and availability info
3. listings.csv - it anchors all data about listings.


## Results<a name="results"></a>
This dataset gives us the insights of the price distribution based on the location, the facility provides and the room types.You can tread more over [here](https://medium.com/@yashvaishnav98/what-did-the-analysis-on-the-boston-airbnb-dataset-give-information-about-d094aac14261).
