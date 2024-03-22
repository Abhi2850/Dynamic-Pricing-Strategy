# Dynamic-Pricing-Strategy

![DPS](https://github.com/Abhi2850/Dynamic-Pricing-Strategy/assets/91343400/f776cb1d-34b7-4783-8d1f-179d1463d9b8)

Tools used🛠: Python, NumPy, Pandas, Machine Learning, Sci-kit Learn, Plotly

🔗dataset link --> https://www.kaggle.com/datasets/arashnic/dynamic-pricing-dataset


The above dataset contains:

Historical sales data
Customer purchase patterns
Market demand forecasts
Cost data
Customer segmentation data,
and Real-time market data.

# Description
Dynamic Pricing is a strategy that harnesses data science to adjust prices of products or services in real-time. By analyzing market demand, customer behavior, demographics, and competitor pricing, companies can optimize revenue by setting flexible prices. This article guides you through creating a data-driven Dynamic Pricing Strategy using Python.

# Objective
The objective is to enhance revenue and profitability for a ride-sharing company by strategically pricing services to match supply and demand dynamics. This approach enables businesses to dynamically adapt prices considering factors such as time of day, day of the week, customer groups, available inventory, seasonal changes, competitor rates, and overall market conditions.

## Steps
* Importing necessary Python Libraries
* Performing EDA
* Visualizing and Analyzing various factors using Scatter plot, Box plot and Heat map.
* Implemented a Dynamic Pricing Strategy: Calculated the demand multiplier by comparing the number of riders to percentiles representing high and low demand levels. If the number of riders exceeds the percentile for high demand, the demand multiplier is set as the number of riders divided by the high-demand percentile. Otherwise, if the number of riders falls below the percentile for low demand, the demand multiplier is set as the number of riders divided by the low-demand percentile.
* Next, we calculated the adjusted ride cost for dynamic pricing. It multiplies the historical cost of the ride by the maximum of the demand multiplier and a lower threshold (demand_threshold_low), and also by the maximum of the supply multiplier and an upper threshold (supply_threshold_high). This multiplication ensures that the adjusted ride cost captures the combined effect of demand and supply multipliers, with the thresholds serving as caps or floors to control the price adjustments.
* Calculated the profit percentage we got after implementing this dynamic pricing strategy
* Checked the relationship between the expected ride duration and the cost of the ride based on the dynamic pricing strategy using Donut plot
* Training a predictive model: -implemented a data preprocessing pipeline to preprocess the data -split the data and train a Machine Learning model to predict the cost of a ride using RandomForestRegressor
* Compared actual and predicted results using scatter plot

# Analysis 


![DPS 1](https://github.com/Abhi2850/Dynamic-Pricing-Strategy/assets/91343400/d8cad65b-9c3b-40b2-b683-ee62f963871c)

![DPS 2](https://github.com/Abhi2850/Dynamic-Pricing-Strategy/assets/91343400/b6f3ffb0-6c14-48ea-875d-4129b9943887)

![DPS 3](https://github.com/Abhi2850/Dynamic-Pricing-Strategy/assets/91343400/1e4c7a3d-2664-4458-ad49-51d77e123e80)


# Output
![DPS 4](https://github.com/Abhi2850/Dynamic-Pricing-Strategy/assets/91343400/56194ebd-ab9d-4070-aed7-ee10674723b3)

