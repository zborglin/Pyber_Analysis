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
![Pyber Q1 & Q2 Fare Collected Over Time](https://github.com/zborglin/Pyber_Analysis/blob/main/Resources/Pyber_summary.png)

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