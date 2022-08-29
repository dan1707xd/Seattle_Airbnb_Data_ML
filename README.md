# Seattle Airbnb Data Analysis (2016-2017)
# Project Motivation
Over the last decade, Airbnb has taken the hotel/hospitality industry by storm and has revolutionized how people tend to make decisions in terms of shelter especially in the short term during their vacations, holidays, business trips etc. This has meant that the Airbnb business has attracted a lot of real estate 
investors who are hungry for better performance and revenue. This notebook attempts to look at the Airbnb business from a host's perspective.

# Installation
Make sure any Python 3.* is installed alongside the pandas, numpy, matplotlib, seaborn and sklearn libraries.


# File Descriptions
The **Seattle Airbnb Dataset** details listings in Seattle, Washington from 01-2016 to 01-2017.
3 Datasets are provided. 
They are: 
1. listings.csv - Survey results regarding characterics of every listing<br />
2. calendar.csv - Collection of price and availability over the year<br />
3. reviews.csv  - Collection of reviews written by users for each listing<br />
The 2 of interest for our analysis are the 'listings' and 'calendar'. For more information regarding the datasets(survey keys can be found at): https://www.kaggle.com/datasets/airbnb/seattle

# Project Details
The analysis conducted in this notebook focusses primarily on data wrangling techniques. The work done encompasses everything from: <br />
1. Dealing with NaNs : when is it acceptable to drop features, impute nulls with the mode or mean depending on the feature dataset and the question we are trying to answer. How to make sure we get most value out of missing values<br />
2. Dealing with categorical variables of varying complexities: Applying the get_dummies method to simple cases and working through intricacies where the categories are in list form <br />
4. Dealing with severely askew features <br />
3. Use correlation techniques (heatmap, groupby) and regression to look at the performance metric of interest.<br />
In our case we look at the following questions:
Assume one is new to the real estate business in Seattle and is looking to buy properties and list them on the Airbnb marketplace:

1. Which property type works best for which zipcode? For example: Entire homes might work better in a zipcode that contains familiy/friendly attractions whereas 
apartments might do better in a zipcode close to downtown where night life is more prominent. But how can we know for sure? <br />
2. What makes a good host? What are preferred host performance metrics? This second quest will basically delineate good host characteristics based on performance.
3. In Seattle, which factors overall are good for revenue? Here, a prediction based (regression) method will be applied to model revenue. 
Finally, the features that dominate that model will be of interest. The analysis that follows in the notebook attempts to best answer these questions dispassionately whilst focussing on the data.
In the evaluation sections of the notebook we: 1. identified the popular zipcodes for any given property type; 2. identified amenities and host attributes that correlate well with revenue and 3. identified features overall that seem to be good for Airbnb business in Seattle. <br />
The key conclusions and a more relaxed discussion of the code can be found in [this blog](https://medium.com/...) post.

# Licensing, Authors, Acknowledgements
Thanks to UDACITY, Kaggle and StackOverflow for providing insight and solution to complications encountered along the way!
