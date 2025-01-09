Olympics Data Analysis

#Project Overview

This project focuses on analyzing the Summer Olympics medal dataset from 1976 to 2008. The analysis identifies key trends, top-performing countries, gender distributions, and sport-wise medal allocations. Insights are visualized using Python plots and interactive Power BI dashboards, enabling a deeper understanding of the data.

#Objectives

The primary goals of this project are:

Analyze trends in Olympic medal distribution over the years.

Identify top-performing countries based on medal counts.

Explore gender distribution and sport-wise medal allocations.

Create engaging visualizations using Power BI and Python.

#Tools and Technologies

This project leverages the following tools and libraries:

Python: For data analysis and visualization (pandas, matplotlib, seaborn)

Power BI: For creating interactive dashboards.

Excel: For initial data exploration and validation.

#Key Insights

#Medal Trends

The overall medal count has increased over the years, with notable spikes in certain years (e.g., 2000 and 2008).

Countries with consistent performance show higher trends.

#Top Countries

The USA leads in medal counts, followed by China and Russia.

Other emerging countries have shown growth over recent Olympic events.

#Gender Distribution

Male participation dominated earlier years, but female participation has significantly increased over time.

Some sports demonstrate near-equal gender representation, while others remain predominantly male or female.

#Sport-Wise Analysis

Athletics, Swimming, and Gymnastics have the highest medal counts.

Emerging sports show promising medal distributions in recent years.

#Folder Structure

├── data/                    # Contains the dataset (Olympics_medals.csv)
├── scripts/                 # Python scripts for analysis
├── visualizations/          # Saved plots (PNG files)
│   ├── medal_trends_line_chart.png
│   ├── top_countries_bar_chart.png
│   └── gender_distribution_pie_chart.png
├── documentation/           # Project documentation and optional report
│   └── project_report.pdf
├── dashboard.pbix           # Power BI dashboard file
├── README.md                # Project documentation

#Steps Followed

1. Data Loading and Cleaning

Loaded the dataset (Olympics_medals.csv) using Python's pandas library.

Performed data cleaning:

Handled missing values.

Renamed columns for consistency.

Filtered data for Summer Olympics (1976-2008).

2. Data Analysis

Analyzed trends in medal counts across years.

Identified top-performing countries and their medal counts.

Explored gender distribution and sport-wise medal allocation.

3. Visualization

Created Python plots (saved in visualizations/):

Line Chart: Medal trends over the years.

Bar Chart: Top countries by medal count.

Pie Chart: Gender distribution of medals.

Designed an interactive Power BI dashboard with filters for Year, Country, and Gender.

4. Documentation

Created a detailed README (this file).

Documented findings in a project report (documentation/project_report.pdf).

5. Submission to GitHub

Organized project files into a structured directory.

Saved visualizations as images in the visualizations/ folder.

Uploaded all files to the GitHub repository.

How to Run the Project

Step 1: Clone the Repository

git clone <repository-url>
cd Olympics-Data-Analysis

Step 2: View Python Analysis

Open the Jupyter notebook (notebook.ipynb) in any Jupyter-compatible environment to explore the Python analysis.

Step 3: Explore Power BI Dashboard

Open dashboard.pbix in Power BI Desktop for interactive visualizations.

#Dataset

Source

The dataset includes medal information from the Summer Olympics (1976-2008), detailing:

Athlete Name

Country

Gender

Sport

Year

Medal Type (Gold, Silver, Bronze).

