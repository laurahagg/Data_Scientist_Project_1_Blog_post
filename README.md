# Project: Write a Blog post about Airbnb-Data from Boston and Seattle
## by Laura Hagg


## Files in the Repository
The following files are in the repository:
Blog_post_code.ipynb
README.md
Blog_post_code.html
Blog_post_by_Laura_Hagg.pdf




## Libraries
for the project the following libraries had been used:
Numpy, Pandas, Matplotlib, Seaborn, Statsmodel, Sklearn


## Neccessary steps during the analysis:
#Gather: 
csv-files about the airbnbs from Boston and Seattle

#Assess:
shape of the dataframes
column names
datatypes

#Clean:
Removing ourliers, missing values
correct wrong datatypes
creating smaller datasets with the needed columns for the analysis

#Analyzse:
Visual analysation and statistics to answer the questions

#Model:
Linear Regressions to see if there is an correlation between the price and the number of rooms.
Linear Regressions to see if there is an correlation between the rating and the property/room type.

#Visualize:
Creating visuals to answer the questions.


## Questions to analyze
#Question 1: What are the differences in the price, the number of rooms and the property and room type in Seattle and Boston?

#Question 2: Which airbnbs have the most and the best reviews - Boston or Seattle?

#Question 3: Is there a correlation between the price and the number of bed- and bathrooms? (Data Modelling)
#
Question 4: Is there are correlation between the property or room type of the airbnb and its rating? (Data Modelling)


## Summary of the results of the Analysis
#Comparing Boston and Seattle: price, room- and property type
The airbnbs in Bosten are more expensive than in Seattle (mean: 172 vs. 128), though the Seattle airbnbs have more bath- and bedrooms according to the mean.
The most airbnbs in Boston are appartments. In Seattle there are a lot of appartments, too, but the most common property type are houses. One interesting fact: In Seattle they rent Treehouses, tents and yurts. They also rent more campers than in Boston.
In both cities we have a similar distribution of the room types: most common are entire homes, on the second place are the private rooms and last are the shared rooms
As in the distribution of the property type seen yet, on Boston are more expensive airbnbs than in Seattle.
On the first view there might be a correlation between the number of bedrooms and the price: It seems, that the price increases when the airbnb hat more bedrooms. You can see this phenomen in Boston and in Seattle, as well. On this point are further investigation neccessary, to verify this relationsship.
The relationsship between the price and the number of bathrooms is not that obviously with visual exploration, but maybe there is an correlation, too!? The Linear Regeression Model in the next step will help us to answer the question.

#Comparing the reviews of the airbnbs:
In Seattle are more airbnbs reviewed than in Boston (83% vs. 77%) and the means of review scores in Seattle are higher than in Boston.

#Here are the results from the Linear Regression Models:
The correlation between the number of rooms and the price has a small r2, that means there is only a weak correlation betweern these values. But the correlation for bedrooms is stronger than for bathrooms. And in Seattle the number of rooms hat a higher influence on the price, because r2 is bigger.
he R squared values are nearly 0, that means there is no linear correlation between the rating and the property/room type of the airbnb.

