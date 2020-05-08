# Impact of weather on house sales

This Project Investigates the impact of weather on house sales and house prices in King County, US. The dependence of house prices on different features of the houses such as square feet living, square feet basement, number of stories, number of bedrooms, etc as well as the impact of different weather conditions such as temperature, cloudliness and humidity on both house prices and sales have been investigated. The explanations for the findings have been included in the Jupyter Notebook.

### The Data

Two datasets have been used for this project.

1- The home sales in King County, US dataset which has been obtained from kaggle https://www.kaggle.com/harlfoxem/housesalesprediction.


2- The historic weather dataset for the days that the houses have been sold, which has been obtained as a json file from openweathermap https://openweathermap.org/.

The datasets have been merged to perform analysis with the purpose of getting insight into the impact of weather on home sales.


### Tools Used

For ths project Python and its modules such as pandas, numpy and matplotlib have been used. The codes have been run on jupyter notebook.

### Data Analysis and Visualization

Here some sample visualizations will be illustrated. For complete analysis results and visualizations please refer to the jupyter notebook.
In the figure below the dependence of house prices on the year in which they have been built has been shown.

<img src="https://github.com/kavehamini/Impact_of_weather_on_home_sales/blob/master/The%20Project/housepricesvsyearbuilt1.png">
    
As it can be seen older houses have higher average prices and then the prices decrease and eventually newer houses also have higher average prices. The older houses may be more expensive due to their historical value and newer houses obviously are more expensive.




### Conclusion

The house prices are dependent on different properties of the houses such as their living area square footage or basement as well as their number of bedrooms and floors. However there is no clear correlation between different weather conditions and house prices or sales. The house sales dataset is from King County, WA where the weather does not fluctuate much throughout the year. With mild winters and not very hot summers, with only few days with temperatures below zero or humidities below 50%, we can say the weather conditions is fairly and always constant in this region. The results however could be different if the data for a region with different weather conditions throughout the year was analyzed


### The Author

This project has been designed and performed by Kaveh Amini (kvhmni@gmail.com).