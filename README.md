# **Pyber_Analysis**
Python Jupyter Notebook Application
-DataFrame management
-Matplotlib, pandas analytics

## **Purpose** 
The **Pyber** technology committee requested analysis of the company rideshare data from January to early May of 2019 presented as a compelling summary for the CEO. Data from multiple sources is integrated to reveal the following analytics:
- Total # of rides *in urban, suburban, and rural cities*
- Total # of drivers *in urban, suburban, and rural cities*
- Total fare collected *in urban, suburban, and rural cities*
- Average fare per ride *in urban, suburban, and rural cities*
- Average fare per driver *in urban, suburban, and rural cities*
- Change in fare collected over time during Q1 and Q2 of 2019
These data are critical to Pyber's planning process for the next fiscal year. Significant resources are available to initiate programs to increase revenue and market share. It is important to make a data-driven decision on the path the company should invest in so that Pyber can remain competitive in the ride-share market. 

## Resources
- city_data.csv, ride_data.csv
- Software: Python 3.7.6

## Analytics Summary
![Pyber Q1 & Q2 Summary](https://github.com/zborglin/Pyber_Analysis/blob/main/Resources/Pyber_summary.png)
#
![Pyber Q1 & Q2 Fare Collected Over Time](https://github.com/zborglin/Pyber_Analysis/blob/main/Resources/Pyber_fare_plot.png)

## Results
The ride sharing data (Q1-Q2 2019) reveals important differences between the rural, suburban, and urban cities within the Pyber portfolio. 
1. Total rides, drivers, and revenue is positively correlated with population. 
-Rides increased from **125 in rural towns** to **1625 in urban centers**.
-Drivers increased from **78 in rural towns** to **2405 in urban centers**.
-Revenue increased from **$4,328 in rural towns** to **$39,854 in urban centers**.
2. Both average Fare per ride and per driver are negatively correlated with population.
- Rides are **more expensive in rural towns** on average **than** they are **urban centers**.
- **More revenue** is collected **per driver in rural towns** than in **urban centers**.
3. Over the Q1-Q2 period, revenues increased in urban and suburban cities but decreased in rural cities.
4. All city types saw a bump in revenue mid to late February, suggesting increased usage for Presidents Day Weekend.

## Strategic Recommendations
1. **Increase fare rates in cities**: Demand is high in urban areas, but this is where the lowest fare per ride and fare per driver exists. Urban Pyber customers likely earn high wages and would continue to utilize the service even if prices increase with the demand. This presents an excellent opportunity to drive higher revenue in Pyber's most important market.
2. **Conduct interviews in rural areas**: It is important to gain a better understanding of the rural market. Revenue is not increasing in these areas as it is in suburban and urban areas. High average fares per ride suggest that typically rides cover long distances, and a low total ride count suggests that few people need to use Pyber for their transportation needs. Conducting interviews with riders and drivers in these areas will reveal if the low ride count is a result of lack of access due to low number of drivers or a sign that the market is too small to warrant any additional investment. 
3. **Invest heavily in suburban cities**: Suburban areas present an excellent balance between ride quantity and ride cost. There are still plenty of people who need rides in these areas and the cost of rides is significantly higher than in urban areas. In addition, a huge increase in demand was exhibited in the last month of Q2 suggesting positive momentum. Suburban areas present a very enticing growth opportunity and would be a great compliment to the established market in urban areas.  