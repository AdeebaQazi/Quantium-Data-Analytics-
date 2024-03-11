# Data Analytics

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendations)

### Project Overview
---
 
- Completed a job simulation focused on Data Analytics and Commercial Insights for the data science team.
- Developed expertise in data preparation and customer analytics, utilizing transaction datasets to extract valuable insights and deliver data-driven commercial recommendations.
- Extended analytical capabilities to identify benchmark stores for conducting uplift testing on trial store layouts, enabling evidence-based decision-making.
- Leveraged acquired data analytics and insights from previous tasks to create comprehensive reports for the Category Manager, facilitating informed strategic decisions and enhancing commercial applications

### Data Sources 

The analysis will be done using 2 data sets "QVI_Transaction_Data" & "QVI_Purchase_Behaviour" containing information regarding the each transaction & customer behaviour.

### Tools

- Python Panda [Data Cleaning & Analysis]
- Python Seaborn [Visualization]
- Canva [Project Presentation]

### Code Guide For Import File 

file_path = "C:/quantium/" (example: I have saved it in C drive.... don't forget to add back slash)

Transaction_data = pd.read_csv(file_path + "Copy & Paste file name")

Transaction_data.head()
 
# Task 1: 
### Data preparation and customer analytics

1. Creating and interpreting high-level summaries of the data.
2. Finding outliers and removing these (if applicable).
3. Checking data formats and correcting (if applicable).

# Task 2: 
### Experimentation and uplift testing

1. Define metrics to select control stores.
2. Analyze trial stores against controls.
3. Use R/Python for data analysis and visualization and summarise findings and provide recommendations.

### Results/Findings

1. Mainstream Young Singles & Couples remain the primary shoppers of chips. 
2. Opportunities have been identified with Young and Older Families.
3. Trial store performance was increased as a result of the new store layout.

### Recommendations
1. The number of chips transactions dramatically increases prior to Christmas. Thus, added visibility to customers via a promotional display or Gondola end would increase purchases driving sales growth over this holiday period. 
2. Mainstream Young Singles & Couples are the primary shopper of chips.
3. Young and Older Families make up 26% of Chips shoppes and on average purchase larger baskets. There is more opportunity for sales with these shoppers. 
4. A control store was constructed to reflect the prior performance of the selected trial store. After implementing the trial store saw significant uplift from the new store layout. 


