# T5_Capital_Bikeshare
This is a data set of Capital Bikeshare users on an hourly basis across Washington D.C.
This data was gathered from 2011 - 2012 and it is created by 
Data Society.
This data was chosen because Riyadh is one of the most densely populated cities in the world, making it one of the most crowded cities, and this is one of the most problems facing the residents of Riyadh, so we looked for a number of new solutions to alleviate this congestion, and we found that the idea of providing bicycles is very suitable, we studied this idea so that we chose one of the most famous and largest degree company in the United States, capital Bikeshare and was chosen based on several factors including that it is based on In Washington, D.C., where congestion is high there and with different seasons, we can predict the number of users based on a certain temperature, in one season of the year, or in a certain weather, and based on the results we decide whether the company is selected and brought to Saudi Arabia?

![](Images/capital-bikeshare-logo.png)
- Link: [data.world](https://data.world/data-society/capital-bikeshare-2011-2012).
- Or you can download it from the attached file.

# Business Problem:
Predict the total users that depends on time.

# Dataset Description:
This data has 17,379 rows, 14 columns.

| Num | Command | Description |
| --- | --- | --- |
| 1  | Date | The date of the day |
| 2  | Season | Seasons of the year -> 1=Spring 2=Summer 3=Fall 4=Winter |
| 3  | Hour | Hour (0 to 23) |
| 4  | Holiday | Is this Day is holiday or not |
| 5  | Day of the Week | Day of the week (0 to 6) |
| 6  | Working Day | Does the day is working day or not  |
| 7  | Weather Type | Weather Type -> 1=Sunny 2=Cloudy 3=Windy 4=Rainy |
| 8  | Temperature F | Normalized temperature in fehrenhite |
| 9  | Temperature Feels F  | Normalized feeling temperature in fehrenhite |
| 10 | Humidity | Normalized humidity |
| 11 | Wind Speed | Normalized wind speed |
| 12 | Casual Users | Count of casual users |
| 13 | Registered Users | Count of registered users |
| 14 | Total Users | Count of total rental bikes including both casual and registered |

# Tools:
- Jupyter notebook
- Libraries(Pandas,Numpy,matplotlib,seaborn,plotly)
- Git Bash
- Zoom

# Questions:
- What are the most crowded days and what time was it?
- What is the difference between registered and casual users?
- How does the season affect the number of users?
- Did the low temperature in winter affect the registered users and casual users?


# Algorithms:
- Linear Regression
- Time Series Data

# MVP:
The MVP goal is to answer at least three of the mentioned questions.

## Authors

- [@Gha7](https://github.com/Gha7)
- [@sole3](https://github.com/sole3)
- [@MahaAlHarqan](https://github.com/MahaAlHarqan)
