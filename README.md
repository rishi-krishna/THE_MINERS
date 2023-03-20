# THE_MINERs

This is a group project which is part of Data-Mining course.


**Team name:** THE MINERS 
**Team members:**
1)	Rishi Krishna Thodupunuri – rthod1@unh.newhaven.edu 
2)	Nikhil Teja Tangella – ntang2@unh.newhaven.edu
3)	Sai Teja Gattu - sgatt4@unh.newhaven.edu


The dataset is called the "Zara US Fashion Products Dataset" and it contains information about products sold by the Zara US stores. Here are some details about the dataset:
•	The dataset includes information on over 21,000 products sold by Zara US from 2017 to 2018.
•	Each product is represented by a unique ID(Product ID) number and includes information such as the product name, product size, Product Category, sizes, Colors, price, state age and Date of sale.
•	The dataset also includes information about the category and subcategory of each product, as well as its color and composition.
•	In addition to product information, the dataset also includes information about Zara US store locations state wise.

**research question:**
Exploring Zara's Innovative Marketing and Supply Chain Strategies to Drive Sales. Identification of Deviations in sales and supply chain based on Customer reviews and sentiment analysis.

As part of Data exploration first we took raw data and pre-processed it by removing unnecessary data from dataset and we structured the data into following columns “Product ID, Product Category,	Product Name, Product price,	Sizes, Coors, State, AGE, Date”.
Below are data exploration techniques we used in this project:
Pre-processing: Converting the raw data into use full data, To create any data model we need to pre-process the un-useful data.
	Filtering: Selecting a subset of the data based on certain criteria, such as state or date range.
	Aggregation: Grouping data by one or more variables to get a summary of the data.
	Outlier detection: Identifying and analyzing values that are significantly different from the rest of the data.
Data cleaning: Removing unnecessary data and structuring the remaining data into columns.
	If there are any Null values and empty cells we removed those Null values using ‘NOT NULL’ Function.

Descriptive statistics: Analyzing the dataset to get a general sense of the data, such as mean, median, mode, standard deviation, etc. 
	We used methods to find overall sales date wise:
	‘DATE TIME’ function
	example- strptime(x,'%m/%d/%Y')) : converts the string value to exact date
	 strftime('%b'), converts the numeric date(month) to string date(month). 
Data visualization: Creating charts and graphs to visually represent the data, such as scatter plots, histograms, box plots, etc.
	We used functions like matplotlib-pyplot, scatter…etc, seaborn,  to represent  data visually.
	Bar graph, we used to represent state wise visualization
	Histographic, point plots …etc 
Cross-tabulation: Analyzing the relationships between two or more variables by creating a contingency table. 
	We used functions like crosstab ..etc

