
# Solar Electricity Analysis and Battery Storage Optimization

This project analyzes solar electricity generation, electricity usage, and battery usage data to evaluate the economic and energy benefits of integrating a battery system into a solar power setup. By leveraging Python and its libraries, the project provides insights into energy efficiency, cost savings, and overall system optimization.

Project Overview
The main goal of this project is to determine the potential benefits of installing a battery to store excess solar electricity. Specifically, the analysis focuses on:

Visualizing solar electricity generation and electricity usage patterns.
Quantifying the electricity bought from the grid without and with a battery.
Modeling the battery charge level and its impact on cost savings.
Aggregating data for monthly trends and visualizations.
While the analysis reveals potential annual savings of $352, it concludes that, at the current system capacity, the cost of installing a $4,000 battery is not economically justified.

Features and Steps
Step 1: Data Visualization and Checks
Goal: Load and explore data from an Excel file.
Tools Used: pandas for data manipulation, matplotlib for visualizing daily average solar electricity generation and usage patterns.
Step 2: Calculating Electricity Bought (Without Battery)
Goal: Compute the amount of electricity required from the grid by subtracting solar generation from usage.
Tools Used: numpy for efficient element-wise calculations.
Step 3: Calculating Excess Solar Generation
Goal: Determine surplus solar electricity by subtracting usage from generation.
Tools Used: numpy for computation and capping negative values.
Step 4: Modeling Battery Charge Level
Goal: Simulate the battery’s charge level over time, considering a maximum capacity of 12.5 kWh.
Implementation: Iterative loop updates battery charge based on available excess solar electricity.
Step 5: Calculating Electricity Bought with Battery
Goal: Recompute electricity bought from the grid, accounting for electricity stored in the battery.
Step 6: Calculating Savings from Installing a Battery
Goal: Evaluate the cost savings by comparing electricity expenses with and without a battery.
Assumptions: Electricity price = $0.17/kWh.
Step 7: Data Aggregation and Visualization
Goal: Aggregate data on a monthly basis and visualize trends using bar plots.
Tools Used: matplotlib for monthly visualizations.
Technologies Used
Programming Language: Python
Libraries:
pandas for data loading, cleaning, and manipulation.
numpy for numerical operations.
matplotlib for data visualization.
datetime for handling time-based data.
How to Use This Repository
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/solar-battery-analysis.git
cd solar-battery-analysis
Install Dependencies: Make sure you have Python 3.7+ installed. Install required libraries using:

bash
Copy code
pip install -r requirements.txt
Run the Analysis: Open the analysis.ipynb notebook in Jupyter and run the cells step by step.

Visualize Results: Check the output plots and data aggregations for insights on solar generation, usage, and battery impact.

Project Files
Solar data analysis.ipynb: Main Jupyter Notebook containing the code and analysis steps.
data/Junior_Data_Analyst_Data.xlsx: Dataset with solar generation, usage, and other parameters.
README.md: Project documentation (this file).
Conclusion
This project demonstrates how data analysis can aid in evaluating renewable energy systems and their optimization. While the battery system provides potential cost savings, the analysis shows that it is not economically viable at the current setup.

Future Work
Analyze scenarios with higher solar generation or reduced battery costs.
Explore dynamic electricity pricing models.
Incorporate machine learning for predictive energy usage and optimization.


Acknowledgments
Special thanks to the Junior Data Analyst program for providing the dataset used in this project.
