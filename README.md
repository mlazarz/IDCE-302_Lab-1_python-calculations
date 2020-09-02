# Lab 1 – Calculations with Python

### *The Issue*
Impervious surfaces like asphault and concrete increase stormwater runoff.  The creation of these non-porious surfaces by paving over agricultural land pose many issues. These problems include:
 - ###### *Greater susceptibility to landslides and flooding which cause property damage and erosion*
 - ###### *Decreased ability to replenish groundwater supply*
 - ###### *Hastens pollution of waterways*
 
If systems are put in place, stormwater runoff can be **captured and recycled**.  This decreases the risks listed above and presents an opportunity for the public to access this water.  Knowing the amount of water that comes off of a plot of developed land, given a rainfall amount, could be valuable information for risk assessment as well as the development of a stormwater catchment system to recycle the water.  The precise number of gallons of water during a storm is important information for the design of the catchment system.  In areas of the world where access to water is scarce and development of impervious surfaces is occurring, the code within the repository may be useful.

### *Case and Code*

Water issues associated with the creation of impervious surfaces is abundant in Kenya.  For example, in the capital city of [Nairobi](https://www.reuters.com/article/us-health-coronavirus-kenya-water/taps-run-dry-in-kenyas-capital-as-coronavirus-spreads-idUSKBN22Q2JN), landslide damage caused by storm water exacerbated water shortages during the global Covid pandemic.  This code focuses on a 1000 square foot developed plot in Kenya and calculates the number of gallons of runoff that is a result of 1 inch of rainfall.  The following are the steps included in this code:

######1.  **Assign values** to the **plot width, plot length, and rainfall amount variables**.  Plot width is 20 feet, plot length is 50 feet, and rainfall amount is 1 inch.
######2.  The plot width and plot length are **converted to inches** by multiplying by *12.0*.
######3.  The **area of the plot** in square inches in calculated by multiplying plot width by plot length.
######4.  The **total amount of runoff** is calculated in cubic inches by multiplying plot area in inches by the rainfall in inches.
######5.  The total amount of runoff is converted from **cubic inches to gallons** by dividing by *231* and then rounded to hundreth decimal place.
######6.  The **outputs are printed** displaying the plot width, plot length, rainfall amount, and total gallons of runoff.

### *Major Errors and Resolution*

While building this code, I came across a syntax error multiple times.  This error occurred every time I attempted to execute my code with a print statement.  The error stated a **TypeError in < module > ()** and that the **'float' object is not callable**.  In debugging this code, I commented out my entire code except for one variable assignment and the print statement for this variable.  I recieved the same TypeError in the () module.  I further simplified my code as shown in the following image and recieved the same error.

![errorimage](pythonerrorLab1.jpg)

My solution to this was that I copy and pasted my entire codeblock into a new Google Colab notebook.  By doing this, the print statements executed with no issues.

###### Author:  Mitchell Lazarz
###### Creation Date: 29 August 2020
###### Python Version Used:  Python 3---Google Colab---Jupyter Notebooks
