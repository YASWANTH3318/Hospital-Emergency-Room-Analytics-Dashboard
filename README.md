# Hospital-Emergency-Room-Analytics-Dashboard
Excel-based hospital operations analytics project including forecasting, what-if analysis, pivot analysis, and an interactive dashboard.

Project Methodology (Step-by-Step Process)
Step 1: Data Loading and Understanding

The hospital emergency room dataset was imported into Microsoft Excel. The dataset contains patient-level records including admission status, wait time, satisfaction score, department referral, age, gender, race, and admission date. Initial exploration was performed to understand the structure and variables in the dataset.

Step 2: Data Cleaning and Preparation

The dataset was cleaned to ensure accurate analysis. The following preprocessing steps were performed:

Checked for duplicate patient IDs.

Verified missing values in satisfaction score and wait time.

Standardized categorical fields such as gender and race.

Converted admission date into time-based attributes including year, month, quarter, and weekday.

Standardized admission flag into binary format (1 = admitted, 0 = not admitted).

Step 3: Feature Engineering

Additional variables were created to improve analysis:

Age groups were created to categorize patients into demographic segments.

Wait time groups were created to analyze operational efficiency.

Admission rate was calculated using the binary admission variable.

These features helped in analyzing patterns across different patient segments.

Step 4: Exploratory Data Analysis

Pivot tables were used to summarize hospital operations and identify patterns. Key metrics calculated include:

Total patient admissions

Admission rate

Average wait time

Average satisfaction score

Department-level performance metrics

These insights helped evaluate operational efficiency and service quality.

Step 5: Operational Performance Analysis

Operational efficiency was evaluated by comparing department performance using:

Average wait time by department

Satisfaction score by department

Admission rate by department

A weighted performance index was created by combining normalized wait time, satisfaction score, and admission rate to rank departments based on overall performance.

Step 6: Scenario Analysis

Two scenario analysis techniques were used:

What-If Analysis

A scenario was created where wait time was reduced by 15% to observe its impact on patient satisfaction.

Goal Seek

Goal Seek was used to determine how wait time would need to change in order to achieve a target satisfaction score.

These analyses help understand the relationship between operational efficiency and service quality.

Step 7: Forecasting Future Admissions

Forecasting models were applied to estimate future hospital demand.

Two forecasting methods were implemented:

Moving Average

Exponential Smoothing

Forecast accuracy was evaluated using Mean Absolute Deviation (MAD). The model with the lowest MAD was selected as the most reliable forecasting method.

Step 8: Admission Influence Analysis

The factors influencing admission decisions were analyzed using pivot-based comparisons. The following variables were evaluated:

Age

Wait Time

Department Referral

Admission rate variation across these variables was calculated to determine which factor has the strongest influence on admission decisions.

Step 9: Dashboard Development

An interactive Hospital Emergency Room Operations Dashboard was developed in Excel to present insights in a visual format.

The dashboard includes four main sections:

Executive Summary

Operational Efficiency Metrics

Service Quality Metrics

Demographic Insights

Interactive slicers allow users to dynamically filter data and explore insights.

Step 10: Key Insights and Decision Support

The final dashboard provides decision-focused insights that help hospital administrators:

Understand operational performance

Identify departments requiring improvement

Predict future patient demand

Improve patient experience and resource planning

## 👤 Author

Beduduri Yaswanth Reddy

Aspiring Data Analyst | Data Visualization Enthusiast

If you found this project useful:

⭐ Star the repository
📩 Connect with me on LinkedIn:
https://www.linkedin.com/in/beduduri-yaswanth-reddy-data-analyst-ai?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BRlTjMwDKRhqo%2Br%2Bin1buTg%3D%3D
