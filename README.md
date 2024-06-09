# Python API
---

**Part 1: Weather**
In this deliverable, I create a Python script to visualize the weather of over 500 cities of varying distances from the equator. I use the citipy Python library , the OpenWeatherMap API , and problemsolving skills to create a representative model of weather across cities.

**Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude.**

Use the OpenWeatherMap API to retrieve weather data from the cities list generated. Next, you'll create a series of scatter plots to showcase the following relationships:
- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

**Requirement 2: Compute Linear Regression for Each Relationship**

To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots. Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r values as you can see in the following image

You should create the following plots:
- Northern Hemisphere: Temperature vs. Latitude
- Southern Hemisphere: Temperature vs. Latitude
- Northern Hemisphere: Humidity vs. Latitude
- Southern Hemisphere: Humidity vs. Latitude
- Northern Hemisphere: Cloudiness vs. Latitude
- Southern Hemisphere: Cloudiness vs. Latitude
- Northern Hemisphere: Wind Speed vs. Latitude
- Southern Hemisphere: Wind Speed vs. Latitude

After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.

**Part 2: Vacation**
In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

The main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.