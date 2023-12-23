# Data Analysis Project: Relationship between Price and Mileage of Car Auctions in USA
## This project aims to explore the relationship between the price and mileage of cars auctioned in USA, using a dataset scraped from AUCTION EXPORT.com. The project involves data cleaning, descriptive statistics, and data visualization using Python libraries such as pandas, numpy, matplotlib, and seaborn.

#Data Source
##The dataset used for this project is vehiclesForProject.csv, which contains information about 150 cars auctioned in USA. The dataset has 10 columns:

>* price: the auction price of the car in US dollars
>* brand: the brand of the car
>* model: the model of the car
>* year: the year of manufacture of the car
>* title_status: the status of the car title (clean or salvage)
>* mileage: the mileage of the car in miles
>* color: the color of the car
>* vin: the vehicle identification number of the car
>* lot: the lot number of the car
>* state: the state where the car was auctioned
>* The dataset was obtained from this link.

# Data Analysis
##The data analysis process consists of the following steps:

>* Importing the necessary libraries and reading the data file
>* Checking the data types, shape, and summary statistics of the dataset
>* Handling missing values by replacing them with the mean of the column
>* Plotting histograms, bar plots, scatter plots, and line plots to explore the distribution and relationship of the variables
>* Interpreting the results and drawing conclusions
>* The code and comments for each step are provided in the data_analysis_project.ipynb file, which is a Jupyter notebook that can be run interactively.

# Results
## The main findings of the data analysis are:

>* The average price of the cars auctioned is $16895, with a minimum of $0 and a maximum of $55000.
>* The average mileage of the cars auctioned is 52298, with a minimum of 0 and a maximum of 204155.
>* The most common car brand is Ford, followed by Dodge and Nissan.
>* The most common car color is white, followed by black and gray.
>* The most common car title status is clean, followed by salvage.
>* There is a negative correlation between price and mileage, meaning that as the mileage increases, the price decreases.
>* The most expensive car is a 1973 Chevrolet Corvette with a price of $30000 and a mileage of 46268.
>* The least expensive car is a 2010 Ford Escape with a price of $0 and a mileage of 0.
>* The car with the highest mileage is a 2008 Ford F-150 with a price of $7500 and a mileage of 204155.
>* The car with the lowest mileage is a 2020 Hyundai Sonata with a price of $21500 and a mileage of 0.
# How to Use
##To use this project, you need to have Python 3 and the following libraries installed:

>* pandas
>* numpy
>* matplotlib
>* seaborn
>* You can install them using the pip command or the conda command if you are using Anaconda.
