### Cricket Data Analytics Project - T20 World Cup Analysis

This project is a comprehensive data analytics journey using the T20 Cricket World Cup data, where we analyze and build insights using web scraping, data cleaning, transformation, and Power BI dashboards. The objective is to select an optimal team of 11 players based on data-driven analysis, helping Earth “compete” against a fictional alien challenge.

### Project Workflow

Web Scraping:
- Data collection was conducted from ESPNcricinfo using Bright Data’s web scraping service. We scraped match results, scorecards, and player statistics.
- The project repository contains JavaScript code for setting up Bright Data collectors, allowing users to automate web scraping tasks for similar datasets.
 
Data Cleaning & Transformation:
- In Python, pandas was used for cleaning and transforming data from JSON files to structured CSV files, preparing it for Power BI visualization.
- Additional transformations included calculating player-specific metrics like batting averages, strike rates, boundary percentages, and economy rates for bowlers.
 
Data Modeling and Calculated Metrics:
- The transformed data was imported into Power BI, where it was modeled into a star schema, linking player and match details with performance data.
- DAX Calculations were used to create custom metrics, such as average runs, strike rates, and dot-ball percentages, making analysis flexible and insightful.
 
Dashboard Design in Power BI:
- Power BI dashboards were built to provide insights into different player roles (e.g., Power Hitters, Anchors, Fast Bowlers).
- Filters and visuals were set up based on predefined parameters for each role, aiding in the selection of the top players for the fictional team.
- Users can interact with the dashboard to analyze specific player performance, compare players, and understand combined averages.
 
Challenge and Final 11 Selection:
- The final 11 players were chosen based on rigorous data insights, aiming to form an unbeatable cricket team.
- An additional challenge for users is included, allowing for customization of the dashboard and enhancement of insights, with a chance to earn scholarships for Codebasics premium courses.

### Learning Outcomes

This project is an end-to-end demonstration of:

- Setting up and automating web scraping
- Cleaning and transforming JSON data with Python
- Data modeling and DAX calculations in Power BI
- Designing insightful dashboards for sports analytics

