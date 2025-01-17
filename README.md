# Wind turbine inspect efficiency with AI

In the face of climate change, the development of renewable energy provided by offshore
wind turbines is essential for sustainability, although their maintenance and safety are
challenging due to their remote location and the high risks and costs associated with
traditional manual inspections. Effective and timely maintenance is crucial for global
investment in wind energy and reliable operation, and an early detection of defects allows
proactive maintenance, reducing secondary damage, catastrophic failures and downtime.
Traditional methods (visual-based or human inspections) are costly and risky but continuous
monitoring using new technologies like Artificial Intelligence helps identify early faults and
schedule maintenance, ensuring sustainable energy production. This study aimed to develop
two predictive models (Support Vector Machine [SVM] and Light Gradient Boosting Machine
[LGBM]) using European wind turbine data from 2018 to automate the inspection of wind
turbines. Also, an explanatory analysis was developed to investigate temporal variability,
correlation and patterns of active power, wind speed, wind direction and power loss. The
SVM was capable of predicting 94% of the active power, while LGBM scored 96%. In
conclusion, this work presents the potential of AI-driven solutions to enhance the operational
efficiency and maintenance of wind turbine operations contributing to the development of the
renewable energy sector.

<img src='https://raw.githubusercontent.com/Alexandre-Di-Nardi/Wind-turbine-inspection-efficiency-with-AI/refs/heads/main/median_per_hour.png' >
Median and interquartile range of active power, wind speed and
wind direction per hour. 

<img src='https://raw.githubusercontent.com/Alexandre-Di-Nardi/Wind-turbine-inspection-efficiency-with-AI/refs/heads/main/median_per_month.png' >
Median and interquartile range of active power, wind speed and
wind direction per month.

<img src='https://raw.githubusercontent.com/Alexandre-Di-Nardi/Wind-turbine-inspection-efficiency-with-AI/refs/heads/main/power_loss_over_time_histogram.png' >
Positive and negative power loss per day (the difference between theoretical power
and active power) per day (kWh) and histogram of power loss per day.

<img src='https://raw.githubusercontent.com/Alexandre-Di-Nardi/Wind-turbine-inspection-efficiency-with-AI/refs/heads/main/power_loss_per_day.png' >
Median and interquartile range of power loss (kWh) per day.

<img src='https://raw.githubusercontent.com/Alexandre-Di-Nardi/Wind-turbine-inspection-efficiency-with-AI/refs/heads/main/predicted_vs_true_power.png' >
Scatter plot and line graph of the relation between wind speed (m/s) and
active power (kWh).


