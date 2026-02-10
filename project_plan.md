<div align="center"> <h2>Predictive Analysis of Customer Churn in IT & Telecom Services</h2> <p><i>An investigation into subscription-based business sustainability</i></p> </div>

<hr>
1. Course Name
Data Analytics-Machine Learning
<hr>
2. Project Title
Data Analysis: Customer Churn Prediction
<hr>
3.<table>
  <thead>
    <tr>
      <th>Student Name</th>
      <th>Role</th>
      <th>Student ID</th>
      <th>Group</th>
      <th>Contact / Details</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Tursinboeva Malohat</b></td>
      <td>Leader</td>
      <td>202490336</td>
      <td>I24C</td>
      <td>+998 99 798 74 04</td>
    </tr>
    <tr>
      <td><b>Umerova Elina</b></td>
      <td>Data Analyst</td>
      <td>202490345</td>
      <td>I24D</td>
      <td>-</td>
    </tr>
    <tr>
      <td><b>Rajabboeva Zevar</b></td>
      <td>System Designer</td>
      <td>202490262</td>
      <td>I24C</td>
      <td>-</td>
    </tr>
    <tr>
      <td><b>Sultanova Amirabegim</b></td>
      <td>Documentation Specialist</td>
      <td>202490319</td>
      <td>I24C</td>
      <td>-</td>
    </tr>
  </tbody>
</table>
<hr>
4. Dataset Information
Dataset Title: Telco Customer Churn (IBM Sample Data)

Source: Kaggle - Telco Customer Churn Dataset

Description of the dataset: This dataset contains 21 features regarding a telecommunications company’s customers, including demographics, account information (contract type, payment method, monthly charges), and subscribed services (Internet, Tech Support, Streaming).

Why this dataset was selected: It represents a classic real-world IT business problem. It provides a mix of categorical and numerical data, requiring significant cleaning and transformation, making it ideal for demonstrating professional data analysis workflows.

Size of dataset: 7,043 rows, 21 columns.

<hr>
5. Project Objectives
Problem Statement: High customer turnover (churn) reduces revenue and increases acquisition costs. The goal is to identify which customers are likely to leave before they cancel their service.

Research Questions:

What is the correlation between contract type (Monthly vs. Yearly) and churn rate?

Do customers with technical support services stay longer than those without?

How does the "Monthly Charge" amount impact the decision to leave?

Expected Insights: Identification of "High-Risk" customer profiles and actionable recommendations, such as offering targeted incentives for long-term contract conversions.

<hr>
6. Data Preparation (Using Pandas)
The preparation phase focuses on ensuring data integrity and usability:

Loading the dataset: Importing the raw CSV file into a Pandas DataFrame.

Cleaning data: Identifying and handling missing values in the TotalCharges column, removing potential duplicate entries, and ensuring all data types are correct for mathematical analysis.

Data transformation: Mapping categorical target variables (Yes/No) into binary integers (1/0) and creating new features such as "Tenure Group" to better categorize customer loyalty.

<hr>
7. Data Analysis Tasks
Using Pandas operations, the following tasks will be performed:

Filtering & Sorting: Identifying high-value customers with high monthly charges who are at risk of churning.

Grouping: Aggregating churn rates by internet service type (Fiber optic vs. DSL).

Pivot Tables: Creating a matrix to analyze the relationship between payment methods and contract duration.

Objective Alignment: Summarizing statistics to directly answer the questions defined in the objectives section.

<hr>
8. Key Findings and Insights
To be filled after project is summarized: 
Contract Influence

Service Impact

Real-world Interpretation
<hr>

<table>
  <thead>
    <tr>
      <th align="left">Week</th>
      <th align="left">Activities</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Week 1</b> (06.Feb ~ 13.Feb)</td>
      <td>Dataset search and project planning</td>
    </tr>
    <tr>
      <td><b>Week 2</b> (13.Feb ~ 20.Feb)</td>
      <td>Data cleaning and preparation (Pandas)</td>
    </tr>
    <tr>
      <td><b>Week 3</b> (20.Feb ~ 27.Feb)</td>
      <td>Exploratory Data Analysis (EDA)</td>
    </tr>
    <tr>
      <td><b>Week 4</b> (27.Feb ~ 06.Mar)</td>
      <td>Data analysis and visualization</td>
    </tr>
    <tr>
      <td><b>Week 5</b> (06.Mar ~ 13.Mar)</td>
      <td>Report writing and presentation preparation</td>
    </tr>
  </tbody>
</table>
<hr>
10. Outcome of the Project
Knowledge Gained: Deep understanding of how to handle imbalanced datasets and translate raw business data into actionable strategic insights.

Skills Developed: Advanced proficiency in Pandas for data manipulation, and the ability to apply statistical logic to business problems.
<hr>
11. Conclusion
Predicting customer churn is vital for any subscription-based IT service. This project demonstrates how data-driven decisions can help a company retain its most valuable customers and optimize its service offerings for long-term growth.
<hr>
12. References
IBM Sample Data Sets: IBM Business Analytics Community

Pandas Documentation: Official Site

Kaggle Community: Churn Analysis tutorials and documentation.
<hr>
13. Appendix
Data Dictionary: Definitions of all 21 columns included in the CSV.
