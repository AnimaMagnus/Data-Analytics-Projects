# Data-Analytics-Projects
Here you can find my projects related to data analytics

# Space Mission Launch Analysis
This project provides a comprehensive exploratory data analysis (EDA) of global space mission launches. Using historical data, the analysis explores trends in space exploration, organizational performance, and the financial factors influencing mission success.

## Project Overview
The goal of this project is to uncover patterns in space missions from the dawn of the space age to the present. The analysis covers everything from launch frequency over time to the correlation between mission costs and their eventual success.

## Key Features
### Data Cleaning & Preparation:
Extensive preprocessing of temporal data (dates and times) and handling of missing financial information.

### Organizational Analysis:
Comparison of mission counts across various space agencies and organizations.

### Temporal Trends:

 - Mission frequency analyzed by year to show the evolution of the space race.

 - Distribution of launches by hour to identify preferred launch windows.

 - Financial Insights: Analysis of mission prices and their relationship with mission outcomes (Success vs. Failure).

### Data Quality Assessment:
A deep dive into "Price Availability," investigating how budget reporting has changed over time.

## Technologies Used
- Python: The core programming language.

- Pandas: For data manipulation and structured analysis.

- NumPy: For numerical operations.

- Matplotlib: For creating static, animated, and interactive visualizations.

- Google Colaboratory: The interactive development environment used for the analysis.

## Dataset
The analysis is performed on the mission_launches.csv dataset, which includes attributes such as:

- Organisation: The agency responsible for the mission.

- Location: The launch site.

- Date/Time: When the mission occurred.

- Rocket Status: Whether the rocket is currently active or retired.

- Price: The cost of the mission (where available).

- Mission Status: Success, Failure, Partial Failure, etc.

## Preview of Analysis
The project addresses several key questions, including:

- What is the relationship between data availability (price reporting) and the era of the mission?

- Which organizations have the highest volume of launches?

- Is there a statistically significant correlation between the cost of a mission and its success rate?

## Findings Summary
- Price Availability: The analysis revealed that over 77% of historical mission price data is missing. The project implements a unique "Price Availability Ratio" to track how reporting standards improved over the decades.

- Launch Trends: Clear peaks in activity correspond with major historical milestones in space exploration.
