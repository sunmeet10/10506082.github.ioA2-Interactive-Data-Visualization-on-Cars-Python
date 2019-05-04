# Python-code
Introduction

We have used a dataset of different types of cars and trucks. Specifications are given for 427 new vehicles for the year 2004. The attributes include price, fuel efficiency, quantitative measurements relating to the size of the vehicle. In this dataset, we have 427 observations with 27 variables. Dataset: 2004 Cars VehicleName	Model Name TypeOfVehicle	Model Type Company Brand of Car Country	Origin of Brand Sedan	Yes/No Sports_Car	Yes/No SUV	Yes/No Wagon	Yes/No Minivan	Yes/No Pickup Yes/No AWD	All-Wheel Drive? Yes/No RWD	Rear-Wheel Drive? Yes/No Retail_Price	Suggested Retail Price, what the manufacturer thinks the vehicle is worth, including adequate profit for the automaker and the dealer Dealer_Cost	Dealer Cost (or "invoice price"), what the dealership pays the manufacturer (U.S. Dollars) Engine_Size	Engine Size (liters) Cyl	Number of Cylinders HP	Horsepower City_MPG	City Miles Per Gallon Hwy_MPG	Highway Miles Per Gallon Weight	Weight (Pounds) Wheel_Base	Wheel Base (inches) Len	Length (inches) Width	Width (inches) Lat	Latitude Long	Longitude Dimension	Length x Width Avg_MPG	Mean of City_MPG & Hwy_MPG

GitHub Link - https://pdhoot16.github.io/DataViz/

Tools for Visualization

Python, Jupyter - Colab

Libraries : Pandas, Numpy, Altair (For Interactive Visualizations)

Contribution:

Each team member has contributes and fulfilled the following tasks.

Poonam Dhoot (10399137) --------------------------------------------------------------------

Environment Set Setup (Installation Of Packages / Libraries)
Data Preprocessing (Data Cleaning , Shaping , Working With Pandas, Altair)
Interactive Dashboard With All Interactive Data Visualization
Report
Sunmeet Thapar (10506082)-------------------------------------------------------------------

Data Preprocessing (Data Cleaning , Shaping)
Interactive Dashboard With All Interactive Data Visualization
Ramya Hunasghatta M (10388022)---------------------------------------------------------------

Determining Initial Questions For Analysis
Kriti Dhyani (10505759)-----------------------------------------------------------------------

Determining Initial Questions For Analysis
Getting Insights about the data and which attributes are related to each other
Dataset Analysis: We have created a dashboard in Python that links all our visualizations and analysis.

To understand, let’s look at the individual aspects of the dashboard

# Horse power vs Retail price($): This scatter plots compares the horse power and retail price of each vehicle.


Number of cars of each company: This bar graph gives number of records of different companies. Toyota, Mercedes and Chevrolet have the high number of records. On selecting each record the dashboard highlights the features of the particular company.  

Country wise analysis: This graph gives the country of the vehicle name along with the retail price. It is known that Germany, USA and Japan are leading manufacturers of cars. These countries manufacture cars for all price ranges. You can find maximum diversity for these countries.





Type of vehicle analysis: From the dataset, we also get the type of vehicle. They can be classified into Wagon, Sports Car, Sedan, SUV, Pickup and Minivan.
 

 

Analysis on the factors that affect the price of the vehicle: In order to analyse the factors affecting the price of the vehicle, we have plotted Cylinder, Engine Size, City Miles per gallon, Highway Miles per gallon, Wheel base, Len, Weight and Width.
 

Actions and analysis on the dashboard: Selecting a single company: The dashboard highlights the graphs filtered for ex. Mercedes.

 

On selecting a particular car type:

 

On filtering a particular model from country:

 