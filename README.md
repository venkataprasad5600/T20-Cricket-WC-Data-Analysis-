# 📌 T20 Cricket World Cup Data Analysis using Power BI

# 📝 Project Overview
This project focuses on analyzing T20 Cricket World Cup data using Power BI. The analysis provides insights into various performance metrics, such as the odds of players, team wins, average bowling statistics, and runs scored by batsmen. The aim is to leverage data to generate actionable insights and create visually engaging reports.

# ✨ Key Features
Odds of Players: Analyzing player performance to understand their contribution and match-winning probability.
Team Wins Analysis: Visualizing the number of matches and tournaments won by each team.
Bowler's Performance: Calculating average bowling economy, strike rate, and wickets taken.
Batsman Performance: Insights into runs scored, strike rates, and consistency.
Custom Insights: Advanced analytics such as:
Player of the Tournament analysis.
Head-to-head team performance comparison.
Match-winning partnerships.

# 📊 Interactive Dashboards: 
Power BI dashboards provide dynamic filtering and slicing for exploring the data interactively.
Dataset Information
The project uses a dataset that includes the following key columns:

# 🏷️ Datasets
Match Details: Match ID, teams, venue,date.
Player Stats: Player name, runs, balls faced, wickets, overs bowled, economy rate.
Team Performance: Team name, total runs scored, wickets lost, match result.
Tournament Data: Year, group stage data, semi-final and final results.

# 🔧 Tools Used
Power BI: For Dat gathering,data cleaning,data visualization and effective dashboards

# 🛠️ project workflow 
Step 1: Data Preprocessing
Gather the dataset (in .csv or .xlsx format).
Ensure the dataset is clean and formatted. Some preprocessing tasks:
Remove duplicates and null values.
Ensure all columns are properly labeled and data types are consistent.
Calculate derived metrics (e.g., player strike rate, bowling economy).
Step 2: Import Data into Power BI
Open Power BI Desktop.
Click on ‘Get Data’ and select your data source (e.g., Excel, CSV, or SQL Server).
Load the dataset into Power BI.
Step 3: Create Relationships
Establish relationships between tables (if using multiple tables).
E.g., link match details to player statistics using match IDs or player names.
Step 4: Create Measures and Calculations
Create calculated columns and measures for analysis:
Player Strike Rate = (Runs Scored / Balls Faced) * 100.
Bowling Economy = Runs Conceded / Overs Bowled.
Win Percentage = (Matches Won / Total Matches Played) * 100.
Use DAX (Data Analysis Expressions) for advanced metrics like team head-to-head win ratios.
Step 5: Design Visualizations
Add the following visualizations:
Bar Chart: Top 10 batsmen by runs scored.
Pie Chart: Team win percentages across tournaments.
Line Chart: Player strike rate trends over multiple tournaments.
Matrix/Table: Detailed match statistics by team and player.
Create slicers for filtering by , team, wins,batesmen,bowlers.
Step 6: Publish and Share
Save the Power BI file (.pbix).
Publish the report to the Power BI Service for online sharing.
Use embedded links to showcase your dashboards.

# License
This project is licensed under the MIT License.
