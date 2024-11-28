COVID-19 Vaccination Rates and Political Leaning in the U.S.
Overview
This project analyzes COVID-19 vaccination rates across U.S. states, focusing on differences between red states (GOP-leaning) and blue states (Democratic-leaning). Using Python for data analysis and visualization, the notebook explores the relationship between vaccination rates and political affiliation.

Key Findings
Higher Vaccination Rates in Blue States:

On average, blue states have significantly higher vaccination rates per 100 people (~10% higher) compared to red states.
A t-test confirmed this difference is statistically significant (p-value = 0.0).
Vaccination Trends:

The average vaccination rate in blue states exceeded 60 vaccinated per 100 people, while red states lagged at around 50 vaccinated per 100 people.
Factors such as vaccine hesitancy, public health campaigns, and political narratives may contribute to this disparity.
U.S. Map Visualization:

A static choropleth map was created to visualize vaccination rates by state, color-coded based on vaccination per 100 people.
The visualization highlights the regional clustering of vaccination disparities.
Skills Demonstrated
Data Analysis:
Used Python libraries like pandas for data manipulation and exploratory analysis.
Statistical Testing:
Performed a t-test to determine the significance of vaccination rate differences between red and blue states.
Data Visualization:
Created visualizations with matplotlib and geopandas, including:
Bar charts showing average vaccination rates by political leaning.
A U.S. choropleth map of vaccination rates.
Geospatial Analysis:
Merged vaccination data with U.S. state shapefiles for geographic insights.
Technologies Used
Python Libraries:
pandas: Data manipulation.
matplotlib: Data visualization.
seaborn: Statistical plotting.
geopandas: Geospatial analysis for static U.S. maps.
scipy.stats: Statistical testing.
Dataset:
COVID-19 vaccination data from Kaggle.
How to Use This Notebook

Clone the repository:
git clone https://github.com/your-username/covid19-vaccination-analysis.git
cd covid19-vaccination-analysis
Install required Python libraries:
pip install -r requirements.txt
Run the Jupyter Notebook:
jupyter notebook vaccination_analysis.ipynb

Future Extensions
Include socioeconomic factors like income, education, and urban/rural divides to deepen insights.
Perform a time-series analysis to track vaccination rates over time in red vs. blue states.
Explore other health indicators to broaden the analysis.
