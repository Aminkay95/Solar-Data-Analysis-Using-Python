Solar Electricity and Battery Usage Analysis
This project involves analyzing solar electricity generation, electricity usage, and battery usage data to assess the potential benefits of incorporating a battery system into the energy setup. Using Python and its powerful libraries, the analysis evaluates cost savings and energy efficiency improvements that a battery system could bring.

Project Overview
The project investigates:

Solar electricity generation.
Electricity usage patterns.
Potential cost savings from installing a battery to store excess solar electricity.
While the analysis indicates that installing a battery saves approximately $352 per year, the high battery cost ($4,000) and system cost ($6,800) make the investment economically unviable at the current solar generation and electricity usage levels.

Features
Data visualization: Visual comparison of solar electricity generation and electricity usage across different hours of the day.
Cost analysis: Quantification of electricity costs with and without a battery system.
Energy modeling: Simulation of battery charge levels to assess its contribution to energy savings.
Monthly aggregation: Insights into energy generation, usage, and cost savings on a broader timescale.
Project Steps
1. Data Visualization and Initial Checks
Goal: Visualize and compare average hourly solar electricity generation and electricity usage.
Libraries: pandas, matplotlib.
Input: Junior Data Analyst _ Data.xlsx.
2. Electricity Bought Calculation
Goal: Determine electricity required from the provider.
Method: Subtraction of solar generation from usage using numpy.
3. Excess Solar Generation Calculation
Goal: Identify surplus solar energy that can potentially charge a battery.
Method: Element-wise subtraction using numpy.
4. Battery Charge Level Modeling
Goal: Simulate battery performance with a capacity of 12.5 kWh.
Method: Iterative calculation of charge levels, capped at maximum capacity.
5. Electricity Bought with Battery
Goal: Calculate reduction in electricity bought due to battery usage.
Method: Adjust electricity bought by factoring in battery-stored energy.
6. Savings Calculation
Goal: Quantify yearly cost savings from the battery system.
Electricity Price Assumption: $0.17 per kWh.
7. Data Aggregation and Visualization
Goal: Monthly aggregation of solar generation, electricity usage, and costs.
Visualization: Bar plots to compare monthly metrics.
Results
Cost Savings: Annual savings of $352.
Conclusion: Installing a battery at the current system capacity is not economically viable.
Tools and Technologies
Programming Language: Python.
Libraries:
pandas: Data manipulation and analysis.
numpy: Numerical operations.
matplotlib: Data visualization.
datetime: Time-related data handling.
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/username/repo-name.git
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Place the Junior Data Analyst _ Data.xlsx file in the root directory.

Visualization Example
The project includes visualizations such as:

Average hourly solar generation vs. electricity usage.
Monthly comparison of energy metrics.
Conclusion
This project demonstrates data-driven decision-making in energy management. While the integration of a battery system offers savings and improved energy efficiency, the high initial cost currently outweighs the financial benefits.

