# FUTURE_DS_01
## Social Media Trend Analysis

# Project Overview

This project analysis project aims to provide insights into the social media trends over the years, by analysing various aspects of the social media data.
The goal is to analyse trends and make data driven recommendation to improve performance by using data visualization and analysis techniques.
The dataset is processed in  Jupyter Notebook, and a Power BI dashboard is created to provide insights.

# Data source 

The social media data is a secondary data which contains information of social media data,it is recorded in an excel file.

# Tools 

Python: Pandas, Seaborn, Matplotlib, Plotly.
Power BI: Interactive dashboards and data visualization.
Jupyter Notebook: Data processing and exploratory analysis.

# Data Cleaning and preparation

In the data preparation phase , below are the steps taken.
   - Loading the dataset
   - Dropping unnecessary columns
   - Handling Duplicates
   - Checking and handling missing values
   - Feature Engineering

# Exploratory Data Analysis

The EDA involves exploring the social media data to answer key questions.
   - Which country is most active in social media?
   - How is the engagement difference in terms of sentiment?
   - Which platform is likely to get more engagement?
   - What is the relationship between hours of the day and engagement level.

# Data Analysis.
Basic summary statistics like mean, median, and value counts are computed.
Visualizations using various plots are generated using libraries like Matplotlib, Seaborn.
Trend Analysis to identifies patterns over time, possibly in social media trends.

pie chart to get the percentage distribution of platform activity.
code:
```python
#Which platform has the highest percentage use
counts=df["Platform"].value_counts()
counts
plt.pie(counts, labels=counts.index, autopct='%1.1f%%', startangle=0)
plt.show()
```

# Findings
- Instagram is the platform with most activity compared to facebook and twitter but with small difference in percentage, aside from percentage instagram has normal distribution of
  engagement interms of counts unlike facebook and twitter which have skewed distribution.
-Between 0900Hours and 2100 Hours there is more engagement .
-USA,CANADA and AUSTRALIA respectively has highest activity in social media.
-The trend in social media activity has increased since 2010 and there was a huge rise in 2023.

# Recommedations
The peak engagement period is between 09:00 and 21:00 Hours, so schedule posts during these hours 
for higher visibility and interaction.
Since the USA, Canada, and Australia have the highest activity, create region-specific content to cater to these audiences.
Collaborate with local influencers in these countries to enhance reach and engagement.
The sharp rise in 2023 indicates increasing adoption, so invest in social media advertising to tap into the expanding audience.
Utilize interactive formats like polls, live sessions, and Q&A to encourage participation for platforms like facebook with skewed engagements.






