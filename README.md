**Introduction**


We have used a dataset of different types of cars and trucks. Specifications are given for 427 new vehicles for the year 2004. The attributes include price, fuel efficiency, quantitative measurements relating to the size of the vehicle. 
In this dataset, we have 427 observations with 27 variables. 
Dataset: 2004 Cars
VehicleName	Model Name
TypeOfVehicle	Model Type
Company	Brand of Car
Country	Origin of Brand
Sedan	Yes/No
Sports_Car	Yes/No
SUV	Yes/No
Wagon	Yes/No
Minivan	Yes/No
Pickup	Yes/No
AWD	All-Wheel Drive? Yes/No
RWD	Rear-Wheel Drive?
Yes/No
Retail_Price	Suggested Retail Price, what the manufacturer thinks the vehicle is worth, including adequate profit for the automaker and the dealer
Dealer_Cost	Dealer Cost (or "invoice price"), what the dealership pays the manufacturer (U.S. Dollars)
Engine_Size	Engine Size (liters)
Cyl	Number of Cylinders
HP	Horsepower
City_MPG	City Miles Per Gallon
Hwy_MPG	Highway Miles Per Gallon
Weight	Weight (Pounds)
Wheel_Base	Wheel Base (inches)
Len	Length (inches)
Width	Width (inches)
Lat	Latitude
Long	Longitude
Dimension	Length x Width
Avg_MPG	Mean of City_MPG & Hwy_MPG

GitHub Link -  https://github.com/sunmeet10/10506082.github.ioA2-Interactive-Data-Visualization-on-Cars-Python

Tools for Visualization 

Python, Jupyter - Colab

**Libraries : Pandas, Numpy, Altair (For Interactive Visualizations)**

Contribution:

Each team member has contributes and fulfilled the following tasks.


Poonam Dhoot (10399137) -------------------------------------------------------------------- 
1.	Environment Set Setup (Installation Of Packages / Libraries)
2.	Data Preprocessing (Data Cleaning , Shaping , Working With Pandas, Altair)
3.	Interactive Dashboard With All Interactive Data Visualization
4.	Report


Sunmeet Thapar (10506082)-------------------------------------------------------------------
1.	Data Preprocessing (Data Cleaning , Shaping)
2.	Interactive Dashboard With All Interactive Data Visualization


Ramya Hunasghatta M (10388022)--------------------------------------------------------------- 
1.	Determining Initial Questions For Analysis


Kriti Dhyani (10505759)-----------------------------------------------------------------------
1.	Determining Initial Questions For Analysis
2.	Getting Insights about the data and which attributes are related to each other

Dataset Analysis:
We have created a dashboard in Python that links all our visualizations and analysis.

To understand, let’s look at the individual aspects of the dashboard
1.	Horse power vs Retail price($): 
This scatter plots compares the horse power and retail price of each  vehicle. 
<img src = "https://github.com/pdhoot16/DataViz/blob/Project-files/Images/dashboard.png">

2.	Number of cars of each company:
This bar graph gives number of records of different companies. Toyota, Mercedes and Chevrolet have the high number of records. On selecting each record the dashboard highlights the features of the particular company.
<img src = "https://github.com/pdhoot16/DataViz/blob/Project-files/Images/Scatter plot.png"> 
 
3.	Country wise analysis: 
This graph gives the country of the vehicle name along with the retail price. It is known that Germany, USA and Japan are leading manufacturers of cars. These countries manufacture cars for all price ranges. You can find maximum diversity for these countries. 

<img src = "https://github.com/pdhoot16/DataViz/blob/Project-files/Images/Country.png"> 

<img src = "https://github.com/pdhoot16/DataViz/blob/Project-files/Images/Country filtered.png"> 

4.	Type of vehicle analysis: 
From the dataset, we also get the type of vehicle. They can be classified into Wagon, Sports Car, Sedan, SUV, Pickup and Minivan.

<img src = "https://github.com/pdhoot16/DataViz/blob/Project-files/Images/Type of vehicle.png"> 

<img src = "https://github.com/pdhoot16/DataViz/blob/Project-files/Images/Type of vehicle filtered.png"> 


5.	Analysis on the factors that affect the price of the vehicle:
In order to analyse the factors affecting the price of the vehicle, we have plotted Cylinder, Engine Size,  City Miles per gallon, Highway Miles per gallon, Wheel base, Len, Weight and Width.

<img src = "https://github.com/pdhoot16/DataViz/blob/Project-files/Images/Common bars.png"> 

Actions and analysis on the dashboard: 
Selecting a single company: The dashboard highlights the graphs filtered for ex. Mercedes.

<img src = "https://github.com/pdhoot16/DataViz/blob/Project-files/Images/Interactive 1.png"> 

On selecting a particular car type:


<img src = "https://github.com/pdhoot16/DataViz/blob/Project-files/Images/Interactive 2.png"> 

On filtering a particular model from country:


<img src = "https://github.com/pdhoot16/DataViz/blob/Project-files/Images/Interactive 3.png"> 
